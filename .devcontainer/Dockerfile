FROM ghcr.io/oca/oca-ci/py3.10-odoo18.0:latest

RUN mkdir /opt/custom
RUN mkdir /opt/config
RUN pip install pre-commit inotify
RUN pipx install oca-maintainers-tools@git+https://github.com/OCA/maintainer-tools.git
RUN apt-get install locales
RUN locale-gen en_US.UTF-8