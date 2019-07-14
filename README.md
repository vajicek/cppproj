# Prerequisites
* cmake
* g++
* libboost-dev

# Build
mkdir build && cd build && cmake ..
make

# Run tests
make test

# Install
cmake -DCMAKE_INSTALL_PREFIX=~/project-bin ..
make install

# Build package
make package
