## Description:


**Related issue (if applicable):** fixes #<home-assistant issue number goes here>

**Pull request in [home-assistant.github.io](https://github.com/home-assistant/home-assistant.github.io) with documentation (if applicable):** home-assistant/home-assistant.github.io#<home-assistant.github.io PR number goes here>

## Example entry for `configuration.yaml` (if applicable):
```yaml

```

## Checklist:
  -[22/8]] The code change is tested and works locally.
  - [22/8] Local tests pass with `tox`. **Your PR cannot be merged unless tests pass**

If user exposed functionality or configuration variables are added/changed:
  - [22/8] Documentation added/updated in [home-assistant.github.io](https://github.com/home-assistant/home-assistant.github.io)

If the code communicates with devices, web services, or third-party tools:
  - [22/8] New dependencies have been added to the `REQUIREMENTS` variable ([example][ex-requir]).
  - [22/8] New dependencies are only imported inside functions that use them ([example][ex-import]).
  - [22/8] New or updated dependencies have been added to `requirements_all.txt` by running `script/gen_requirements_all.py`.
  - [22/8] New files were added to `.coveragerc`.

If the code does not interact with devices:
  - [22/8] Tests have been added to verify that the new code works.

[ex-requir]: https://github.com/home-assistant/home-assistant/blob/dev/homeassistant/components/keyboard.py#L14
[ex-import]: https://github.com/home-assistant/home-assistant/blob/dev/homeassistant/components/keyboard.py#L54
