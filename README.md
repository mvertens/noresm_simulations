# noresm_simulations

The noresm_simulations repository is dedicated to tracking of NorESM experiments.

The idea for this repository was stolen shamelessly from the [NCAR amwg_dev repo](https://github.com/NCAR/amwg_dev).

## To start a new development simulation, follow these steps:
- Determine what branch your experiment case directory will live on, current supported branches are:
 -- noresm25_preindust_coupled
 -- noresm25_preindust_amip
- Determine a case name for your run using the proposed nameing convention of
    ``shortcompsetname_codeversion_grid_somekindofinfo_yyyymmdd``
- Open an issue and fill out the template
  -- include a link to the branch in the issue (when pushed)
- Create your case directory and using the script (TBD) push your case directory to the branch
