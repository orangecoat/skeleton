{exec} = require 'child_process'

task "compile", "compile the project's coffeescript", ->
  exec "coffee -c -o compiled/js/ coffeescripts"

task "watch", "watch the project's coffeescripts to autocompile on change", ->
  exec "coffee -c -w -o compiled/js/ coffeescripts"
