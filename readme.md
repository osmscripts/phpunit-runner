Command-line utility for running `phpunit` script installed into the project in current directory.

## Installation ##

Run the following commands in shell:

	composer -g config repositories.osmscripts_core vcs git@github.com:osmscripts/core.git
	composer -g config repositories.osmscripts_phpunit_runner vcs git@github.com:osmscripts/phpunit-runner.git
	composer -g require osmscripts/phpunit-runner

## Usage ##

Run the following commands in shell:

	cd {project_dir}
	phpunit

## License And Credits ##

Copyright (C) 2019 - present UAB "Softnova".

All files of this package are licensed under [GPL-3.0](/LICENSE).
