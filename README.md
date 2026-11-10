# LisztQWV_Letters

Digital workspace for transcribing, metadata enrichment, and TEI-XML encoding of Franz Liszt's correspondence for the **Liszt Quellen- und Werkverzeichnis (LQWV)**.

## Project Overview
This repository contains the workflow and edition files for ~1.600 manuscript pages from the Goethe- und Schiller-Archiv (GSA) (signature group GSA 59/56,1–97,2). The pipeline utilizes multimodale Vision LLMs for automated HTR transcription, metadata integration, and TEI-XML alignment.

## Repository Structure
* `transcription_tests/` – Experimental prompt logs and raw test outputs (`.txt`).
* `raw_transcripts/` – Initial automated transcription outputs and raw XML extracts (`.xml`).
* `tei_xml/` – Fully edited, validated, and TEI-XML compliant edition files (`.xml`).

## Workflow & Data Pipeline
1. **Source Data:** IIIF manifests & XML metadata from GSA.
2. **HTR & Vision Processing:** Automated layout analysis and text extraction using an LLM.
3. **Structuring:** Automated tagging and manual post-correction into valid TEI-XML.

## Acknowledgments & Attribution
This workspace adapts software patterns and processing pipelines originally developed by **Richard Freedman** ([Liszt_Letters](https://github.com/RichardFreedman/Liszt_Letters)), licensed under the **Apache License 2.0**.
