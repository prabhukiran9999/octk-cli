# OCTK CLI
`octk` (Open Cloud Toolkit) is a cli tool built using [Cobra](https://github.com/spf13/cobra) and [Cobra Generator](https://github.com/spf13/cobra/tree/master/cobra). This tool serves as a central place to nicely package scripts that are frequently used by Cloud Pathfinder admins. The goal of this tool is to streamline daily admin tasks as well as bring new admins up to speed faster.

## Prerequisites

  - Go `brew install go`

## Usage
install the cli locally:
```bash
go install github.com/bcgov/octk-cli/octk@latest
```
to see usage instructions try `octk` or `octk --help`

## Development
Use the [Cobra Generator](https://github.com/spf13/cobra/tree/master/cobra) to create new commands, arguments or flags.

  ```bash
  go install github.com/spf13/cobra/cobra@latest
  ```

## Useful Guides
  [How to create a CLI in golang with cobra](https://towardsdatascience.com/how-to-create-a-cli-in-golang-with-cobra-d729641c7177)