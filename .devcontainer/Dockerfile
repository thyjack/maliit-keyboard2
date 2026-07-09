FROM mcr.microsoft.com/devcontainers/cpp:debian13

# Install build dependencies, Qt5, Maliit, and other libraries
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends \
        build-essential \
        cmake \
        doxygen \
        gettext \
        pkg-config \
        libglib2.0-dev \
        libanthy-dev \
        libchewing3-dev \
        libhunspell-dev \
        libpinyin-dev \
        maliit-framework-dev \
        qtbase5-dev \
        qtdeclarative5-dev \
        qtfeedback5-dev \
        qtmultimedia5-dev \
        qtquickcontrols2-5-dev \
        clangd \
        python3 \
        python3-pip \
        python3-setuptools \
        python3-dev \
    && apt-get clean && rm -rf /var/lib/apt/lists/*
