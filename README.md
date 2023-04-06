1. get started with travis (refer to links getting started)
2. Make sure nodeks is up to date. I think v14 or higher
3. Install Playwright (https://playwright.dev/docs/intro)

	npm init playwright@latest

Should get this if successful

✔ Success! Created a Playwright Test project at /home/nag/Documents/playwright

Inside that directory, you can run several commands:

  npx playwright test
    Runs the end-to-end tests.

  npx playwright test --ui
    Starts the interactive UI mode.

  npx playwright test --project=chromium
    Runs the tests only on Desktop Chrome.

  npx playwright test example
    Runs the tests in a specific file.

  npx playwright test --debug
    Runs the tests in debug mode.

  npx playwright codegen
    Auto generate tests with Codegen.

We suggest that you begin by typing:

    npx playwright test

And check out the following files:
  - ./tests/example.spec.ts - Example end-to-end test
  - ./tests-examples/demo-todo-app.spec.ts - Demo Todo App end-to-end tests
  - ./playwright.config.ts - Playwright Test configuration

Visit https://playwright.dev/docs/intro for more information. ✨

Happy hacking! 🎭

4.Create git repo
5.install travis on repo (use getting started link -- optional)
	Select payment plan for travis if haven't already
6.Actions should be setup on the repo now, I think every push will trigger a run.

