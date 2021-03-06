Buckley Lab SIP protocols 
=========================

## Printing protocols (conversion of protocols to PDF)

* View any Markdown file on GitHub, then in your URL bar of your browser 
  replace the git**hub**.com part of the URL with git**print**.com
* The Markdown file will be rendered as a PDF for easy printing or downloading.

## Updating non-markdown versions of protocol files

* Please don't edit the Word or html files directly!
* The markdown files (*.md) serve as the template files for all of the other formats (eg., html or docx).
* The bash scripts (eg., md2html.sh) will convert all files ending in '.md' to a specified format.
	* Example usage: `./md2html.sh` 
		* This will creat a html file for each corresponding markdown file.


## Working in the lab

* [lab_etiquette](./working_in_the_lab/lab_etiquette.md)
* [undergrad_expectations](./working_in_the_lab/undergrad_expectations.md)

## Pipeline steps

* Soil sampling
	* [soil_sampling_protocol](./sampling/soil_sampling_protocol.md)
	
* Microcosm setup
	* Ashley's priming experiment setup (Fall 2013)
		* [SIP_microcosm](./microcosm/SIP_microcosm.md)
	* Nick's full C-cycle pilot experiment setup (Fall 2014)
		* [SIP_fullCyc_pilot_microcosm](./microcosm/SIP_fullCyc_pilot_microcosm.md)
	* Nick's 2nd full C-cycle experiment setup (Fall 2015)
		* [SIP_fullCyc2_microcosm](./microcosm/SIP_fullCyc2_microcosm.md)
		
* Microcosm headspace CO<sub>2</sub> measurements (via GC/MS)
	* [CO2_batch_run](./GCMS_operation/CO2_batch_run.md)

* Nucleotide extraction
	* [DNA_RNA_extraction_Protocol](./nucleotide_extraction/DNA_RNA_extraction_Protocol.md) 

* __If DNA:__ CsCl fractionation
	* [CsCl_fractionation](./CsCl_fractionation/CsCl_fractionation.md) 

* __Else if RNA:__ CsTFA fractionation
	* [RNA_SIP](./RNA_SIP/RNA_SIP.md)

* Nucleotide quantification:
	* [Picogreen](./nucleotide_conc/picogreen.md)

* Nucleotide sample concentration
	* [speed-vac](./speed-vac/speed-vac.md)

* Pippin Prep
	* [Pippin_prep](./Pippin_prep/Pippin_prep.md)

* Fraction nucleotide quantification:
	* [picogreen](./nucleotide_conc/picogreen.md)

* MiSeq library prep:
	* [Illumina_barcoding_protocol](./library_prep/Illumina_barcoding_protocol.md)


## Others

* Cellulose farming
	* Cellulose production
		* [CelluloseProductionProtocol](./cellulose_farming/CelluloseProductionProtocol.md)
	* Cellulose grinding:
		* [CelluloseGrindingProtocol](./cellulose_farming/CelluloseGrindingProtocol.md)
	
* Plant stimulant
	* [Substrate_Additions_MicrobSuccession](./plant_stimulant/Substrate_Additions_MicrobSuccession.md)

* Soil geochemistry
	* [pH](./soil_geochemistry/pH.md)
	* [organic_content](./soil_geochemistry/organic_content.md)
	* [water_holding_capacity](./soil_geochemistry/water_holding_capacity.md)



## Workflows

### Bulk DNA sequencing of the 16S rRNA gene

* [Nucleotide extraction](./nucleotide_extraction/DNA_RNA_extraction_Protocol.md)

* [Sephadex column clean-up](http://www.gelifesciences.com/webapp/wcs/stores/servlet/productById/en/GELifeSciences/27533001)

* [Nucleotide quantification via Picogreen](./nucleotide_conc/picogreen.md)

* [16S rRNA amplicon library prep](./library_prep/Illumina_barcoding_protocol.md)



### Microcosm -> gradient fractionation -> 16S rRNA gene sequencing

* [Nucleotide extraction](./nucleotide_extraction/DNA_RNA_extraction_Protocol.md)

* __Optional:__ Concentrating via [speed-vac](./speed-vac/speed-vac.md)

* [PippinPrep](./Pippin_prep/Pippin_prep.md)

* [Nucleotide quantification via Picogreen](./nucleotide_conc/picogreen.md)

* [CsCl_fractionation](./CsCl_fractionation/CsCl_fractionation.md) 
	* Including desalting

* [Nucleotide quantification of fractions via Picogreen](./nucleotide_conc/picogreen.md)

* [16S rRNA amplicon library prep](./library_prep/Illumina_barcoding_protocol.md)
	* For automated generation of the Excel files needed for the PCR assay, 
		see the fractionSelectFor16S-PCR.ipynb notebook in the SIPdb repo.
