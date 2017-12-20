```
rails generate rspec:install
bundle binstub rspec-core
bin/rspec
rails generate model user username:string
bin/rake db:migrate RAILS_ENV=test
bin/rspec
```
```
Pending:
  User add some examples to (or delete) /Users/ming/src/rails/rspec-rails-app/spec/models/user_spec.rb
    # Not yet implemented
    # ./spec/models/user_spec.rb:4

Finished in 0.00049 seconds (files took 0.97144 seconds to load)
1 example, 0 failures, 1 pending
```
