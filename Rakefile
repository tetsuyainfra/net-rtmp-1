require 'rake/testtask'
require 'rake'

task :default => :test

Rake::TestTask.new do |t|
	t.libs << "test" 
	t.test_files = FileList['test/test_*.rb']
end