# Tags

- Realizar o commit normalmente:

```bash
git commit -m "Mensagem aqui"
```

- Realizar o push normalmente:

```bash
git push origin master
```

---

## Criar tag

```bash
git tag -a 1.0.0 -m "Comentário"
```

- No lugar do `1.0.0` pode adicionar a sua versão

- Por fim realizar o push da tag:

```bash
git push origin master --tags
```

PACKAGE_VERSION=$(node -p -e "require('./package.json').version")

echo $PACKAGE_VERSION  