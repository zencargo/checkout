# checkout

This action wraps actions/checkout and adds custom git config before checkout is done

## Example usage

```yaml
- name: Check out source code
  uses: ./.github/actions/checkout
```

With fetch-depth:

```yaml
- name: Check out source code
  uses: ./.github/actions/checkout
  with:
    fetch-depth: 0
```

## Inputs

### working-directory

**Required**

Path of the module to check, relative to the GitHub workspace.
