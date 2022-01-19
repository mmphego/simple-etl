FROM apache/airflow:2.2.3
ADD requirements.txt /usr/local/airflow/requirements.txt
RUN pip install --no-cache-dir -U pip setuptools wheel
RUN pip install --no-cache-dir -r /usr/local/airflow/requirements.txt
