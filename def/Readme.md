# How-to run

## Run Singularity

* singularity exec ~/mcstas_3-1.sif mcgui

## Build 

* time singularity build mcstas_trn.sif def/mcstas.def

* ./mcstas_trn.sif -v

## CLI commands

* default command to run ’mcstas’ – e.g. mcgui, use exec command

* singularity exec mcstas_trn.sif mcgui

## shell 

* singularity shell /home/user_name/mcstas_trn.sif
