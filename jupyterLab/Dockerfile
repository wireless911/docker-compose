FROM jupyter/tensorflow-notebook
COPY requirements.txt /tmp/
RUN pip install --requirement /tmp/requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple && \
    fix-permissions $CONDA_DIR && \
    fix-permissions /home/$NB_USER