Minimal reproduction for https://github.com/vercel/turbo/issues/3758

1. Run `yarn turbo prune --scope="@namespace/app" --docker`
2. Compare `turbo.json` with `out/full/turbo.json`
3. Note that all of the `env` keys are just `"env": []`
