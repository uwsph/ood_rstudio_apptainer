# RStudio as Open OnDemand App

An interactive Open OnDemand app that launches an RStudio Server using a Apptainer image.

Based on:

* [bc\_osc\_rstudio\_server](https://github.com/OSC/bc_osc_rstudio_server).
* [ood\-bih\-rstudio\-server](https://github.com/bihealth/ood-bih-rstudio-server).

## License

- MIT, see `LICENSE` file.

## Container Building

The app is designed for using the [Rocker Project](https://rocker-project/) built Docker containers, or those based on them.

For example, you convert the latest rocker/verse image into an Apptainer image with:

```bash
apptainer pull docker://rocker/verse:latest
```
