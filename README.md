# README

This is a Rails app configured how I like it. It's meant to be used for prototyping 

## Getting started

### Rename project

- Find and replace instances of `RailsStarter`, `rails-starter`, and `rails_starter`.

### Set up dependencies

- `bundle install`
- `yarn install`
  
### Set up database

- `bundle exec rails db:setup`

### Start the app

- `hivemind Procfile.dev`

## System Requirements

- Ruby 3.0.2
- Node 14.18.1
- PostgreSQL
- hivemind

## Development Gems

- [rubocop-rails](https://github.com/rubocop/rubocop-rails) with [standard](https://github.com/testdouble/standard) rules
- dotenv-rails
- pry-byebug
- pry-rails
- annotate
- better_errors
- bullet
- letter_opener
  
## Testing Gems

- rspec-rails
- shoulda-matchers
- factory_bot_rails
- faker
- simplecov
- webmock

## To do

- Add JS linters
- Add JS testing tooling
