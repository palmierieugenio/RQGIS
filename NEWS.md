# RQGIS 0.1.0.9000

* `run_qgis` now stops if the output shapefile created by QGIS is empty.
* Removing a bug from `run_qgis`. Function argument `load_output` now checks if the QGIS output was really created before trying to load it.
* `run_qgis`-message: Use qgis:creategrid instead of qgis:vectorgrid.
* vignette update (MacOSX and homebrew installation)
* Fine-tuning of the documentation files
* Deleting redundancies in functions `build_cmds`, `check_apps` and `execute_cmds`
* Removing empty string from `find_algorithms` output
* Added a `NEWS.md` file to track changes to the package.




