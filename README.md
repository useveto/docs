# Veto Documentation

Source files for the Veto documentation at [docs.veto.tools](https://docs.veto.tools).

## Local development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint):

```bash
npm i -g mint
```

Preview locally:

```bash
mint dev
```

View at [localhost:3000](http://localhost:3000).

## Validation

```bash
mint broken-links    # check internal links
mint validate        # validate build
```

## Deployment

Changes pushed to the default branch are deployed automatically via the Mintlify GitHub app.
