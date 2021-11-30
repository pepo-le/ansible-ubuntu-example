# How to Use
```
$ ansible-playbook site.yml
```

# Encrypt Secret
## Encrypt
```
$ ansible-vault encrypt secret.yml
```
## Using
```
$ ansible-playbook site.yml --ask-vault-pass
```
