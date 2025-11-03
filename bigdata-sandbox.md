# Data Engineering Sandbox VM – Setup Summary
This environment provides a unified sandbox for local experimentation with big data tools and frameworks like Hadoop, Spark, Pig, MongoDB, Flink, and Jupyter. Designed for research, education, and prototyping.

**System Overview**

- OS: Ubuntu 20.04 LTS
- User: mararow_dsv
- Password: unspecified
- Python: 3.10.12
- Java: OpenJDK (version compatible with Spark & Hadoop)
- Package Manager: pip3, system packages via apt
- Notebook Interface: Jupyter Notebook

**Installed Tools (- version)**
- Hadoop - 3.4.1
- Spark - 3.5.1
- Pig 0.17 runs locally
- MongoDB  -
- Flink -
- Zeppelin -
- Jupyter -

Resource recommendations
* Hadoop - 2 GB, 5 GM disk, 2+ CPU
* Spark - 2 GB, 5 GM disk, 2+ CPU
* Pig - 2 GB, 5 GM disk, 2+ CPU
* MongoDB - 2 GB, 5 GM disk, 2+ CPU
* Jupyter - 2 GB, 5 GM disk, 2+ CPU
* Flink - 2-4 GB,... 

**Capabilities**
Data Processing, Analytics, and ML
- Run Hadoop MapReduce jobs locally
- Run Spark jobs
- Execute Pig scripts that read/write
- Use PySpark in Notebooks (Zeppelin and Jupyter)
- Rim Flink Streaming job
- Rum machine learning tasks on big data environments (distributed environments)
- Do NLP, such as ....
- Jupyter Notebooks for - Python, PySpark, Pig, PyFlink, CLI, Shell Scripting, etc.
- Zeppeline Notebooks for - Python, Pyspark, Pig, PyFling, CLI, visualizations
- MongoDB for document-based database examples


**Project Structure
**
/home/mararow_dsv/

├── hadoop/          # Hadoop binaries & config

├── spark/           # Spark installation

├── pig/             # Apache Pig

├── flink/           # Flink (to be reinstalled)

├── notebooks/       # Jupyter notebooks

├── scripts/         # Sample .pig, .py, .sh scripts

├── data/            # Input/output files

└── logs/            # Runtime logs

**Author**
Workneh Y. Ayele (Ph.D.)
Stockholm University - DSV



