# OpenML Labs blog

This repository serves as the blog for the OpenML Labs. It uses Quarto to render the blog posts from markdown and jupyter notebooks. 

## How to write a post?

- Clone this repository
- Install quarto : [Here](https://quarto.org/docs/get-started/)
- Create a new folder in the `posts` directory with the name of your post
  - `git checkout -b <post-name>`
  - Create a markdown file or a jupyter notebook in the folder
  - Add a header to the start of the file as below
    ```yaml
    ---
    toc: true
    layout: post
    description: Experimenting with LLM temperature and its effects on answer quality
    categories: [llm]
    title: Experiments with Temperature
    author: Subhaditya Mukherjee
    date : 2024-07-08
    ---
    ```
  - Add any images or other files that are needed for the post in the folder
- `git add . && git commit -m "Added post" && git push`
- Create a pull request to the `main` branch
- Once the PR is merged, the post will be live on the blog