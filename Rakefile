require 'bundler'
Bundler::GemHelper.install_tasks

require 'rake/testtask'

Rake::TestTask.new(:test) do |test|
  test.libs << 'lib'
  test.test_files = FileList['test/test_*.rb']
  test.verbose = false
  test.warning = false
end

task :default => [:build]
