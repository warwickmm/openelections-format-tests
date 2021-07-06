# OpenElections Data Format Tests
A collection of tests to validate the format of OpenElections data files.

## Usage
```
$ python3 run_tests.py <absolute path to data repository>
```
The data are expected to be contained in CSV files that reside under
directories named by the corresponding election years.  For example,

```
<data repository>
|
|-- 2000
|   |-- a.csv
|   |-- b.csv
|-- 2001
    |-- counties
        |-- c.csv
        |-- d.csv
        |-- e.csv
```