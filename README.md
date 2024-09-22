# @wycey/renovate-conf

Renovate configuration for wycey repositories.

## Usage

1. Setup Renovate in your repository.
2. Add a `renovate.json` file to `.github` directory in your repository.
3. Add the following configuration to the `renovate.json` file:

```json
{
  "extends": ["github>wycey/renovate-conf"]
}
```

You can override the configuration by adding your own configuration in the `renovate.json` file.
