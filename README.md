# cdm-data-loader-utils
Repo for CDM input data loading and wrangling



**Set up conda environment**  
```bash
conda env create -f env.yml
conda activate genome_loader_env
```

**Run tests**
```bash
 python -m unittest discover -s tests -p test_genome_loader.py
```


**For running tests with checkm2 (Time taking so disabled by default)**
```bash
   conda activate genome_loader_env
   checkm2 database --download
```

