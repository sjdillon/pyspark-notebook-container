# pyspark-notebook in container

- run spark and a Jupyter in a container

# overview

- the notebook runs in the container
- the code is from this [article](https://levelup.gitconnected.com/using-docker-and-pyspark-134cd4cab867)
- this simply includes a docker-compose and the csv in the repo

# get started

- clone this repository
  - `git clnone https://github.com/sjdillon/pyspark-notebook-container`

- navigate to directory
  - `cd pyspark-notebook-container`
- start the docker container
  - `docker-compose up`
- click the jupyter link in the output -  look for something like this: 
  - ``pyspark-notebook_1  | [I 23:51:10.941 NotebookApp] http://127.0.0.1:8888/?token=2d5b03bba48fd696cc0ffa3435a84c2b01e39ee025a5d647``
- open the notebook and run
  - ``work/nb.ipynb``













