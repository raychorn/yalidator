yalidator
=========

Windows-based command line YAML Validator

Usage: yalidator [options]

Options:
  -h, --help            show this help message and exit
  -i INPUT, --input=INPUT
                        specify the input file name (expects a YAML file)
  -v, --verbose         verbose
  
yalidator -i "c:\path-to-your-yaml-file.yml"

If successful, you will see the JSON from your YAML file otherwise you will see an error message indicating the problem(s) with the YAML.
