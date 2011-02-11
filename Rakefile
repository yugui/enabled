task :default => 'enabled.gem'

rule 'enabled.gem' => %w[ enabled.gemspec ] do
  sh "gem build enabled.gemspec"
end
