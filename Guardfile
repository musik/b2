# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard :bundler do
  watch('Gemfile')
  # Uncomment next line if your Gemfile contains the `gemspec' command.
  # watch(/^.+\.gemspec/)
end

guard 'rails',:port=>4100,:server=>:unicorn do
  watch('Gemfile.lock')
  watch(%r{^(config/environments/|lib)/.*})
end

