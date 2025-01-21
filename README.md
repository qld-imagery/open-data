# Open Data - Queensland Imagery & Elevation

[![STAC Browser Badge](https://img.shields.io/badge/Open_in_STAC_Browser-%2309B3AD?style=flat&label=Queensland%20Imagery%20and%20Elevation%20Data&labelColor=%23144E63)](https://radiantearth.github.io/stac-browser/#/external/qspatial-data.s3-ap-southeast-2.amazonaws.com/aerial_v2/catalog.json)
[![AWS Badge](https://img.shields.io/badge/Open_in_Registry_of_Open_Data_on_AWS-%23FF9900.svg?logo=amazon-web-services&logoColor=white&labelColor=%23232F3E)](https://registry.opendata.aws/qld-imagery-elevation/)

The Department of Natural Resources and Mines, Manufacturing, and Regional and Rural Development (NRMMRRD) makes Queensland's publicly owned aerial imagery and elevation data freely available to use under an open licence. You can access this through [QImagery](https://qimagery.information.qld.gov.au/), [Queensland Globe](https://qldglobe.information.qld.gov.au/), [Spatial Portal](https://spatial-img.information.qld.gov.au/arcgis/rest/services), or the [Registry of Open Data on AWS](https://registry.opendata.aws/qld-imagery-elevation/).

## Quickstart

Browse the archive with [STAC Browser](https://radiantearth.github.io/stac-browser/#/external/qspatial-data.s3-ap-southeast-2.amazonaws.com/aerial_v2/catalog.json) or access the catalog directly:

- [https://qld-imagery.s3-ap-southeast-2.amazonaws.com/catalog.json](https://qld-imagery.s3-ap-southeast-2.amazonaws.com/catalog.json)
- [https://qld-elevation.s3-ap-southeast-2.amazonaws.com/catalog.json](https://qld-elevation.s3-ap-southeast-2.amazonaws.com/catalog.json)

## Background

Details about the collection and dataset

- Naming
- Tools
- Usage

### AWS Access

NRMMRRD owns and maintains a public bucket which is sponsored and shared via the [Registry of Open Data on AWS](https://registry.opendata.aws/qld-imagery-elevation/) `s3://qld-imagery` in `ap-southeast-2`.

Using the [AWS CLI](https://aws.amazon.com/cli/) anyone can access all of the imagery specified in this repository.

```
aws s3 ls --no-sign-request s3://qld-imagery/
```

## License

All metadata and docs are licensed under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/).

For [more information on imagery attribution](https://www.linz.govt.nz/products-services/data/licensing-and-using-data/attributing-elevation-or-aerial-imagery-data).
