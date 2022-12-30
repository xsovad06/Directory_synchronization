# Directory_synchronization

Program that enables one-way periodical synchronization of two directories, source and replica.

## Usage
For correct program operation positional arguments needs to be set:

- `source` -> <str> absolute path to the source directory to be synchonized")
- `destination` -> <str> absolute path to the destination directory of synchonization")
- `interval` -> <int> synchonization interval in seconds
- `logs` -> <str> absolute path to the logs destination (log file is named `synchronization.log`)
