## superusers

_Playbook_, создающий группу пользователей superusers куда входят пользователи user2 и user3, и которая, выполнив `sudo -i`, сможет повысить свои полномочия и стать root-пользователем.

```
ansible-playbook superusers.yml -K --ask-vault-pass
```
