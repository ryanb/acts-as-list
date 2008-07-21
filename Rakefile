require 'rubygems'
require 'rake'
 
begin
  require 'echoe'

  Echoe.new('acts-as-list', '0.1.2') do |p|
    p.summary        = "Gem version of acts_as_list Rails plugin."
    p.description    = "Gem version of acts_as_list Rails plugin."
    p.url            = "http://github.com/ryanb/acts-as-list"
    p.author         = ['Ryan Bates', 'Rails Core']
    p.email          = "ryan (at) railscasts (dot) com"
  end

rescue LoadError => boom
  puts "You are missing a dependency required for meta-operations on this gem."
  puts "#{boom.to_s.capitalize}."
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }
