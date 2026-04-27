# Recipes

Notes from the [softbake.dev](https://softbakedev.github.io) kitchen.

Practical recipes about product design, sprint planning, baker agents, testing, and delivery, written for humans who ship software with code agents.

*Faster. Leaner. Always human checked.*

## Articles

The first recipe in the series is [How to turn an idea into a product recipe](./how-to-turn-an-idea-into-a-product-recipe/), filed under product design and weighing in at about a seven minute read.

More recipes are still proofing in the [`planning/`](./planning/) folder. Next up is [Planning a sprint kitchen for baker agents](./planning/planning-a-sprint-kitchen-for-baker-agents.md), filed under delivery, followed by [Body shopping versus agent shopping](./planning/body-shopping-versus-agent-shopping.md), a side by side look at the two delivery models that fund most software work today.

## How this blog is organised

Each published article lives in its own folder, written in plain Markdown so it renders cleanly on GitHub and can be embedded into the [softbake.dev](https://softbakedev.github.io) site. Upcoming articles sit in the `planning/` folder as short coming soon notes until they are ready to ship. The top level of this repository looks roughly like the tree below.

```text
recipes/
├── README.md
├── how-to-turn-an-idea-into-a-product-recipe/
│   └── README.md
└── planning/
    ├── README.md
    ├── planning-a-sprint-kitchen-for-baker-agents.md
    └── body-shopping-versus-agent-shopping.md
```

Mermaid diagrams render natively on GitHub, so flow charts and sequence diagrams sit inline with the prose instead of hiding in image files.

## Contributing a new recipe

To add a new recipe, create a new folder named after the article slug in kebab case, drop a `README.md` inside with the article content, and open a pull request. The master chief tastes every batch before it ships.
