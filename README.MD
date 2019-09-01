# Be Sure Your Computer has GFLAGS library

cmake -DCMAKE_INSTALL_PREFIX=/usr/local -DBUILD_SHARED_LIBS=ON -DGFLAGS_NAMESPACE=google -G"Unix Makefiles"