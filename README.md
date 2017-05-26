# Przydatne skrypty

## Logowanie po SSH bez hasła

```
ssh-keygen
```

Następnia dodaj go do serwera produkcyjnego

```
ssh-copy-id -i ~/.ssh/id_rsa.pub mat2tab@mat2tab.inf.ug.edu.pl
```
