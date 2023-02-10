# Workflows
- In this CI/CD script we going to create workflows for github actions of our orchestration in our projects, to manage pushes and pull requrests in our projects.
- We can also add actions
    - like searching action location, public repo
        ~~~
        uses: {owner}/{repo}@{ref}
        uses: octocat/super-cool-action@v1
        ~~~
    - we can target the same repo as our workflow
        ~~~
        uses: ./path/to/action
        uses: ./.gihub/actions/my-action-location
        ~~~
    - using a Docker image.
        ~~~
        uses: docker:://{image}:{tag}
        uses: docker:://hello-world:latest
        ~~~
- This is some example in terms how we going to source what we need.
