FROM mambaorg/micromamba:0.15.2:latest
RUN micromamba install -y -n base -c conda-forge \
        python=3.8 \
        rasterio \
        matplotlib \
        jupyter && \ 
        micromamba clean --all --yes