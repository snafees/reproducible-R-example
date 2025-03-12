FROM condaforge/mambaforge

RUN conda config \
    --add channels defaults \
    --add channels bioconda \
    --add channels conda-forge

RUN conda install -y samtools