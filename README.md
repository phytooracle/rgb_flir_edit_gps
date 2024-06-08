# Edit GPS

This script takes updated geocoordinates calculated by MegaStitch and applies them to GeoTIF images.

## Inputs
This script takes a CSV file containing geocoordinates.

## Outputs
This script outputs GeoTIFs with updated geocoordinates.

## Arguments and Flags
* **Positional Arguments:** 
    * **The TIF file to edit:** 'tif'
      
* **Required Arguments:**
    * **CSV file with updated coordinates:** '-c', '--csv'                 

* **Optional Arguments:**
    * **Output directory:** '-o', '--outdir', default='gpscorrect_out'
