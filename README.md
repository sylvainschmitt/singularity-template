Template Singularity container
================
Sylvain Schmitt
April 28, 2021

**Bionformatics package Template**

Template is a set of utilities that Blah.

Template Version: X.X.X

\[URL\]

Singularity container based on the recipe: Singularity.template.sif

Package installation using Miniconda3 V4.7.12

Image singularity (V\>=3.3) is automatically test and built and pushed
on the registry using
[test.yml](https://github.com/sylvainschmitt/singularity-template/blob/main/.github/workflows/test.yml)
&
[builder.yml](https://github.com/sylvainschmitt/singularity-template/blob/main/.github/workflows/builder.yml)

**build**:

``` bash
sudo singularity build Singularity.template.sif Template_0.0.1
```

**pull**:

``` bash
singularity pull https://github.com/sylvainschmitt/singularity-template/releases/download/0.0.1/singularityhub-singularity-deploy.latest.sif
```

**snakemake**:

``` python
    singularity: 
        "https://github.com/sylvainschmitt/singularity-template/releases/download/0.0.1/singularityhub-singularity-deploy.latest.sif"
```
