
# Data Product Canvas - Berlin LOR Day Care Centers

## Metadata

* owner: Open Lifeworlds
* description: Data product providing Berlin daycare center data on different LOR hierarchy levels
* url: https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-daycare-centers
* license: CC-BY 4.0
* updated: 2025-11-06

## Input Ports

### berlin-lor-geodata

* manifest URL: https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-geodata/refs/heads/main/data-product-manifest.yml

### berlin-daycare-centers-source-aligned

* manifest URL: https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-daycare-centers-source-aligned/refs/heads/main/data-product-manifest.yml

### berlin-lor-population-source-aligned

* manifest URL: https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-population-source-aligned/refs/heads/main/data-product-manifest.yml

## Output Ports

### berlin-lor-daycare-centers-geojson
name: Berlin Lor Daycare Centers Geojson
* owner: Open Lifeworlds
* url: https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-daycare-centers/tree/main/data/03-gold/berlin-lor-daycare-centers-geojson
* license: CC-BY 4.0
* updated: 2025-11-06

**Files**

* [berlin-lor-daycare-centers-2025-10-city.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-daycare-centers/refs/heads/main/data/03-gold/berlin-lor-daycare-centers-geojson/berlin-lor-daycare-centers-2025-10-city.geojson)
* [berlin-lor-daycare-centers-2025-10-details.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-daycare-centers/refs/heads/main/data/03-gold/berlin-lor-daycare-centers-geojson/berlin-lor-daycare-centers-2025-10-details.geojson)
* [berlin-lor-daycare-centers-2025-10-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-daycare-centers/refs/heads/main/data/03-gold/berlin-lor-daycare-centers-geojson/berlin-lor-daycare-centers-2025-10-district-regions.geojson)
* [berlin-lor-daycare-centers-2025-10-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-daycare-centers/refs/heads/main/data/03-gold/berlin-lor-daycare-centers-geojson/berlin-lor-daycare-centers-2025-10-districts.geojson)
* [berlin-lor-daycare-centers-2025-10-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-daycare-centers/refs/heads/main/data/03-gold/berlin-lor-daycare-centers-geojson/berlin-lor-daycare-centers-2025-10-forecast-areas.geojson)
* [berlin-lor-daycare-centers-2025-10-planning-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-daycare-centers/refs/heads/main/data/03-gold/berlin-lor-daycare-centers-geojson/berlin-lor-daycare-centers-2025-10-planning-areas.geojson)


### berlin-lor-daycare-centers-statistics
name: Berlin Lor Daycare Centers Statistics
* owner: Open Lifeworlds
* url: https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-daycare-centers/tree/main/data/03-gold/berlin-lor-daycare-centers-statistics
* license: CC-BY 4.0
* updated: 2025-11-06

**Files**

* [berlin-lor-daycare-centers-statistics.json](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-daycare-centers/refs/heads/main/data/03-gold/berlin-lor-daycare-centers-statistics/berlin-lor-daycare-centers-statistics.json)


## Observability

### Quality metrics

 * name: geojson_property_completeness
 * description: The percentage of geojson features that have all necessary properties

| Name | Value |
| --- | --- |
| berlin-lor-daycare-centers-2025-10-city.geojson | 100 |
| berlin-lor-daycare-centers-2025-10-districts.geojson | 100 |
| berlin-lor-daycare-centers-2025-10-forecast-areas.geojson | 100 |
| berlin-lor-daycare-centers-2025-10-district-regions.geojson | 100 |
| berlin-lor-daycare-centers-2025-10-planning-areas.geojson | 100 |


## Classification

**The nature of the exposed data (source-aligned, aggregate, consumer-aligned)**

consumer-aligned


---
This data product canvas uses the template of [datamesh-architecture.com](https://www.datamesh-architecture.com/data-product-canvas).