[![Build Status](https://travis-ci.org/neuron-js/pyneuron.svg?branch=master)](https://travis-ci.org/neuron-js/pyneuron)

# pyneuron

Python utilities and middleware for neuron.js

## Install

```sh
$ pip install pyneuron
```

## Usage

```py
from pyneuron import neuron

neuron_instance = neuron(
  dependency_tree=dependency_tree,
  decorate=decorator,
  path='mod'
)
```

## License

MIT
