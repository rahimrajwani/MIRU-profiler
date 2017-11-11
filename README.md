# MIRU-profiler

MIRU-profiler -- performs digital 24-loci MIRU-VNTR typing for *Mycobacterium tuberculosis*

## For Windows 10 users

Should you wish to run MIRU-profiler on Windows 10 please install bash-shell first:

https://www.windowscentral.com/how-install-bash-shell-command-line-windows-10

## Video demonstration

[![Please click for a video demonstration](https://github.com/rahimrajwani/MIRU-profiler/blob/master/Demonstration.png)](https://youtu.be/0TWioBzPcNU)


## Install dependencies

EMBOSS (version:6.6.0.0)
```
sudo apt install emboss
```

## Usage
```
./MIRU-profiler [options] -i input_file.fasta
```
###### For execution in a batch-mode
Provide a directory name followed by wild-card(*) in single quotes. Example:
```
./MIRU-profiler [options] -i 'input_dir/*'
```
## Options
```
-h  = Prints this help text
-e  = Define the acceptable variation (in bp) between amplicon size in sequence and reference MIRU table [Default: 5]
-i  = Define input file or a directory of fasta files [Required]
-o  = Set the output directory for the intermediate files [Default: OUTPUT]
-s  = Set the directory for supporting files [Default: Supporting_files]
```

