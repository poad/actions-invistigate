# actions-invistigate

```yaml
      - name: github
        env:
          GITHUB: ${{ toJSON(github) }}
        run: echo ${GITHUB} | jq .
```
