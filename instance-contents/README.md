# Shhh... something amazing is brewing here 🧪
Here starts the journey to create an amazing stack. We have set up a [`.github/workflows/ci.yml`](.github/workflows/ci.yml) to run some checks on your stack and help you debug it. Get started by editing [`.github/stacks/stack.yml`](.github/stacks/stack.yml) to configure the stack the way you want. Use the comments in it and this [doc](https://github.com/github/github-stacks/blob/main/adrs/stack-schema.md) to get an idea of the syntax.

Points to keep in mind:
1. **Stacks can be only consumed through releases** - `Use this template` button uses the latest release. So make sure to create a release on an update to be able to test out the changes (we have better experiences coming 🙏). You can uncomment a step in [`.github/workflows/ci.yml`](.github/stacks/stack.yml) which creates a release on every push.
2. **Check your CI runs if you have issues with the stack** - We have a workflow set up to run some checks on your stack template. If you get - `Issues found in stack template` while releasing, the logs of `Run Pre Publish Checks` should have an answer to why its failing. If not, it's probably an issue with the init workflow file (non existent or improper trigger) or the app section (invalid slug or more than 100 apps defined). You can reach out to us for help.
3. **Definitely reach out to us once you finish authoring a stack** - We can help you out on releasing this stack to the marketplace so others can discover your innovation. We also would love to meet you and take your feedback on the whole experience. 

Reach out to us in this [channel](https://github.slack.com/archives/C02KXRVHTB5) or feel free to DM me or anyone in the stacks team for any help 😁.
Thank you so much for trying out stacks 💖
