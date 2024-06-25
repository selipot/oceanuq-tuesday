# oceanuq-tuesday
A repository for the material needed for the Wednesday activities of the OceanUQ Summer School

Files description:

- `environment.yml`: yaml file listing python dependencies
- `get-mur-sst-data.ipynb`: A notebook showing how to read MUR data from the archive present in an AWS S3 bucket.
- `interpolate-mur-atlantic`: A notebook that shows how I actually "nearest interpolated" the MUR data (SST and its uncertainty) onto a limited subset of drifter data in the North Atlantic. This creates the two GDP datasets in NetCDF files `gdp_atlantic.nc` and `gdp_9am_atlantic.nc`, the latter being a subset of the drifter data at 9:00am only, the analysis time for MUR. These two datasets are not in this github repository but in the Google Drive Folder for Tuesday activities.
- `read_mur.ipyn`: A messy notebook that shows how I actually assembled a larger MUR subset after obtaining the data directly from NASA PODAAC instead of AWS.
