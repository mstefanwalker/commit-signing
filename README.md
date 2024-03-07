# commit-signing

```
gpg --full-generate-key

gpg --list-secret-keys

gpg --armor --export <sec>

git config commit.gpgsign true

git config user.signingkey <sec>

git config user.email <key-email>
```

[docs.github.com/signing-commits](https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits)

[docs.github.com/generating-a-new-gpg-key](https://docs.github.com/en/authentication/managing-commit-signature-verification/generating-a-new-gpg-key)
