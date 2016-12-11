# OpenNGC
A license friendly NGC (New General Catalogue) database

Version 0.1

Contact: mattia dot verga at tiscali dot it



### PRESENTATION

OpenNGC is a database containing positions and main data of
NGC (New General Catalogue) objects. Unlike other similar databases which
are released with license limitations, OpenNGC is released under
CC-BY-SA-4.0 license, which allows the use for a wider range of cases.

For information about data fields contained in the database, please see
the file NGC_guide.txt.


### DATA SOURCES

OpenNGC has been built by merging data from:

 - NASA/IPAC Extragalactic Database
   http://ned.ipac.caltech.edu/
   This research has made use of the NASA/IPAC Extragalactic Database (NED)
   which is operated by the Jet Propulsion Laboratory,
   California Institute of Technology, under contract with the
   National Aeronautics and Space Administration.

 - HyperLEDA database
   http://leda.univ-lyon1.fr
   We acknowledge the usage of the HyperLeda database (http://leda.univ-lyon1.fr)

 - SIMBAD Astronomical Database
   http://simbad.u-strasbg.fr/simbad/
   This research has made use of the SIMBAD database, operated at CDS, Strasbourg, France

 - HEASARC High Energy Astrophysics Science Archive Research Center
   http://heasarc.gsfc.nasa.gov/
   We used several databases from HEASARC such as mwsc, lbn, pn and WDS

Where incongruences between catalogs was found we used NED as source.

#### NOTES ON OBJECT DATA

 - All object types: coordinates are taken from NED
 
 - Open clusters (OCl | *Ass): where available, diameter is taken from 
   Milky Way Star Clusters Catalog table, central_radius parameter.
   MWSC object number is reported for reference.

 - Planetary Nebulae (PN): we merged data from Galactic Planetary Nebulae Catalog
   and SIMBAD. Diameter and central star magnitudes are taken from plnebulae table,
   fields opt_diameter, umag_cstar, bmag_cstar, vmag_cstar. Other object magnitudes
   (B - V - J - H - K) are taken from SIMBAD because they're referred to more recent
   measures, but if not available we used fields jmag, hmag, kmag.

### STATUS
Currently importing data.
Objects of type galaxy are completed.
Other object types till NGC3000 completed.
