# Pipeline Template plugin for Buildkite

This plugin can be used to construct pipelines with specific sets of mandatory steps, for governance and compliance purposes.

## Example

Add the following to your `pipeline.yml`:

```yml
steps:
  - plugins:
      - mkmrgn/pipeline-template-buildkite-plugin:
          team: [team name]
```

## Configuration

### `team` (Required, string)

Specifies what team specific yaml file will be incorporated into the resulting pipeline.

## Developing

## Contributing
