---
title: Genomics Pipeline
description: Scalable Nextflow pipeline for whole-genome sequencing analysis with automated QC and variant calling.
tags: [Nextflow, Python, Bioinformatics, AWS]
github: https://github.com/priyeshagrawal
---

A production-grade genomics pipeline built with Nextflow for processing whole-genome sequencing data at scale.

## Features

- Automated quality control and adapter trimming
- Alignment with BWA-MEM2 and variant calling with GATK
- Cloud-native execution on AWS Batch
- Comprehensive HTML reports with MultiQC

## Architecture

The pipeline follows a modular design pattern with each analysis step encapsulated as an independent Nextflow process, enabling easy customization and extension.
