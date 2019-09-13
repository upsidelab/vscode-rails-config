# VS Code Rails Configuration template
VS Code configuration template for Rails projects

This repository includes base tasks configuration file for working effectively
with Ruby on Rails projects in Visual Studio Code.

## Defined tasks

- test - runs the whole rspec suite
- test:current (default test task) - runs rspec test for current file
- lint - runs rubocop on the whole project
- lint:fix - runs rubocop on the whole project and automatically fixes issues
- db:migrate - runs database migrations
- build (default build task) - runs lint and test on the whole project
