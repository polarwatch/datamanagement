# Dataset ID: nesdis_blendedsic_shem_daily

## General Information
- [Link to Data Landing Page](https://polarwatch.noaa.gov/catalog/ice-conc-sh-blended-nesdis/preview)
  - Name : Blended Sea Ice Concentration from AMSR2/VIIRS Daily 1km, Antarctic
  - Version : 1.0
  - Contact : Richard Dworak
  - Data Published : 12/18/2023
- Is this raw data or a derived/processed data product? _Derived_
- Is this observational data, simulation/model output, or synthetic data?  _Synthetic_ 
- Is the data single-source or aggregated from several sources? _Aggregated_

## Data Quality
- Timeliness:
  - Will the dataset be updated? _Yes, it will be updated. _
    - Updated when new data are added _daily_
    - Will there be different stages of the update?  _No_
 
- Data completeness 
  - Is there any documentation about the completeness of the dataset? _Yes_
    - [link to documentation](https://www.mdpi.com/2072-4292/13/15/2982)
  - How complete is the dataset compared to the expected spatial coverage?
    _Complete_
  - How complete is the dataset compared to the expected temporal coverage?
    _Complete_
- Data consistency
  - Is this dataset self-consistent in that its units, data types, and parameter names
    do not change over time and space? _Yes_
  - Is this dataset’s units, data types, and parameter names consistent with similar data
    collections? _Yes_
  - Are there processes to monitor for units, data types, and parameter consistency? 
    _No_ 
    - If yes, what measures are taken? _Manual review_ [TODO]


::: {.callout-tip title="Note"}
* Check for pole hole, flag values?
* Data consistency: create data management plan and add review process
:::

- Data bias
  - Is there known bias in the dataset? _No_
    - [link to documentation](https://www.mdpi.com/2072-4292/13/15/2982)
  - Have measures been taken to examine bias? _No_
  - Is there reported bias in the data? _No known bias_
  - Is there quantitative information about data resolution in space and time? _Yes_
  - Are there published data quality procedures or reports? _No_ 
  - Is the provenance of the dataset tracked and documented? _No_
  - Are there checksums / other checks for data integrity? _No_
  - What is the size of the dataset? Depending on the resource, this might be total data volume,
    dimensionality, number of images, data files, table rows, image size, etc.  _ approximately 15 ~ 540 MB (file size per day)_

## Data Documentation
- Does the dataset metadata follow a community/domain standard or convention? _Yes_
  - If the metadata follows a community/domain standard, which standard is it? _CF-1.6, ACDD-1.3, NOAA CDR v1.0, GDS v2.0, COARDS_
  - Is the dataset metadata machine-readable? _Yes_
  - Does it include details on the spatial and temporal extent? _Yes_
- Is there a comprehensive data dictionary/codebook that describes what each element of
  the dataset means? parameters? _Yes_
  - Is the data dictionary standardized? _Yes_
  - Is the data dictionary machine-readable? _Yes_
  - Do the parameters follow a defined standard? _Yes_
    - If the parameters follow a defined standard, which standard it is? _CF-1.6_
  - Are parameters crosswalked in an ontology or common vocabulary (e.g. NIEM)? _Not applicable_
- Does the dataset have a unique persistent identifier, e.g. DOI?  _Yes_ (CHECK DOI)
- Is there contact information for subject-matter experts? _Yes_
- Is there a mechanism for user feedback and suggestions? _Yes_
- Are there example codes/notebooks/toolkits available showing how the data can be used? _Yes_ 
- What is the license for the data? 
  - [NCEI Data Licensing](https://www.ncei.noaa.gov/archive#:~:text=Because%20works%20of%20the%20US%20government%20are,license%20to%20that%20portion%20of%20its%20holdings.) _These data may be redistributed and used without restriction_
  - Is the license standardized and machine-readable (e.g. Creative Commons)?  _Yes_
- Has this dataset already been used in AI or ML activities? _No_
- Are there recommendations on the intended use of the data, and uses that are not recommended? _Yes_ [TODO: link to documentation]

## Data Access  
- What is/are the major file formats? netcdf
  - Is this format machine-readable? _Yes_ 
  - Is the data available in at least one open, non-proprietary format? _Yes_
  - Are there tools/services to support data format conversion? _Yes_
    - If so, provide the link to the tools/services
- Data delivery: [ERDDAP](https://polarwatch.noaa.gov/erddap/griddap/nesdis_blendedsic_nhem_daily.html)
  - Does data access require authentication (e.g., a registered user account)? _No_
  - Can the file be accessed via direct file downloading or ordering?  _Yes_
  - Is there an Application Programming Interface (API) or web service to access the data?
    _Yes_
  - If there is an API, does the API follow an open standard protocol (e.g., OGC)? _Yes_
  - If there is an API, is there documentation for the API? _Yes_
    - If “Yes”, please provide a URL to the documentation.
  - Is the data available publicly via cloud services?  _Yes_
- For restricted data, have measures been taken to provide some access while still applying
   appropriate protection for privacy and security?  _Yes_
  - Has the data been aggregated to reduce granularity?  _Yes_ 
  - Has the data been anonymized / de-identified? _Not applicable_
  - Is there secure access to the full dataset for authorized users?  _No_

## Data Preparation

- Have null values/gaps been filled? _Yes_
- Have outliers been identified? _No_
- Is the data gridded (regularly sampled in time and space)? _Yes_
    - _Regularly gridded in space and constant time-frequency_
  - If the data is gridded, was it transformed from a different original sampling? 
    _Yes,  from a different regular sampling_
  - If the data is resampled from the original sampling, is the data also available at the original sampling? 
    _Yes_
- Are there associated targets or labels for supervised learning techniques (i.e., can this be
  used as a training dataset for supervised learning techniques)? _Yes_


##  Additional Metadata
* PolarWatch Metadata: https://polarwatch.noaa.gov/erddap/info/nesdis_blendedsic_shem_daily/index.html 

