
## Readme

To enable husky hooks add this to `package.json`:
```
"husky": {
    "hooks": {
      "pre-commit": "node ./scripts/pre-commit",
      "pre-push": "node ./scripts/pre-push"
    }
  },
  ```
  