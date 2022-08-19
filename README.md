# title

example to reproduce bug https://github.com/renovatebot/renovate/issues/16749


renovate will stop scanning your dependencies if a comment is found

```
dependencies:
  ansible.posix: "1.0.0"
  # comment whih makes renovate end parsing
  # latest is 2.6.1
  ansible.utils: "1.0.0"
```
