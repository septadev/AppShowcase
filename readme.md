SEPTA's App Center is a public showcase for apps made using SEPTA's API.

## Adding a project

1. Fork this repository;
2. Add your image (748x600) on `/resources` (e.g. `my-project.jpg`);
3. Add your project info on `/src/data/project.json`;
4. Submit a pull-request.

If you have any trouble doing it, check pull requests to see others' submits.

## Working locally

To run the project, follow the steps bellow after cloning the repository:

```bash
npm install
gulp compile:all
gulp lift
```

Then access the application on http://localhost:8000/

### Development

For developing, simply run the command `gulp watch:all` for automatic re-compiling on file changes.

### Deploying on gh-pages

To deploy on production simply run the following tasks on your local environment

```bash
gulp compile:all
gulp deploy
```

Then follow the instructions on your terminal.
