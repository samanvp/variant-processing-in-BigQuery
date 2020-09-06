## Disclaimer
This is not an official Google product.

# GCP Variant Transforms 
[GCP Variant Transforms](https://github.com/googlegenomics/gcp-variant-transforms) is a tool for processing VCF files and importing genomics variants into [BigQuery](https://cloud.google.com/bigquery/). Storing variants in BigQuery enables users to quickly sort and filter variants and extract aggregate stats from them. Performing similar tasks using conventional tools such as [VCFtools](http://vcftools.sourceforge.net/) if not impossible, is extremely hard. 

In this repo we are showcasing some sample queries applied to datasets hosted publicly on BigQuery: 
* [gnomAD](https://console.cloud.google.com/marketplace/product/broad-institute/gnomad)
* [1000Gemoes](https://console.cloud.google.com/marketplace/product/bigquery-public-data/human-variant-annotation-public).

Note that you can run these queries at no cost, assuming use of the [1TB free offering of BigQuery](https://cloud.google.com/bigquery/pricing#on_demand_pricing).
