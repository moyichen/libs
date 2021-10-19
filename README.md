# libs
开源库



# A 2D graphics library 
# https://www.cairographics.org/
git clone git://anongit.freedesktop.org/git/cairo
git clone git://anongit.freedesktop.org/git/pixman.git
git clone git@gitlab.com:cairo/cairo-demos.git

# Cocos2d-x is a suite of open-source, cross-platform, game-development tools used by millions of developers all over the world.
# https://github.com/cocos2d/cocos2d-x
git clone https://github.com/cocos2d/cocos2d-x.git
cd cocos2d-x
python download-deps.py
git submodule update --init
cd ..

# Dear ImGui is a bloat-free graphical user interface library for C++.
# https://github.com/ocornut/imgui
git clone https://github.com/ocornut/imgui.git

# Minimalistic GUI library for OpenGL
# https://github.com/wjakob/nanogui
git clone https://github.com/wjakob/nanogui.git
cd nanogui
git submodule update --init
cd ..

# A small C library for building user interfaces with C, XML and CSS.
# https://github.com/lc-soft/LCUI
git clone https://github.com/lc-soft/LCUI.git

# GLFM is an OpenGL ES layer for mobile devices and the web.
# https://github.com/brackeen/glfm
git clone https://github.com/brackeen/glfm.git

# A multi-platform library for OpenGL, OpenGL ES, Vulkan, window and input
# https://github.com/glfw/glfw
git clone https://github.com/glfw/glfw.git

# SwiftShader is a high-performance CPU-based implementation of the Vulkan, OpenGL ES, and Direct3D 9 graphics APIs. Its goal is to provide hardware independence for advanced 3D graphics.
# https://github.com/google/swiftshader
git clone https://github.com/google/swiftshader.git

# Yoga is a cross-platform layout engine which implements Flexbox.
# https://github.com/facebook/yoga
git clone https://github.com/facebook/yoga.git

# Garbage Collector
# https://github.com/ivmai/bdwgc
git clone https://github.com/ivmai/bdwgc.git

# Cross-platform, graphics API agnostic
# https://github.com/bkaradzic/bgfx
git clone https://github.com/bkaradzic/bgfx.git

# Antialiased 2D vector drawing library on top of OpenGL for UI and visualizations.
# https://github.com/memononen/nanovg
git clone https://github.com/memononen/nanovg.git

# Skia is a complete 2D graphic library for drawing Text, Geometries, and Images.
# https://skia.org/
git clone https://skia.googlesource.com/skia.git

# A platform independent standalone library that plays Lottie Animation.
# https://github.com/Samsung/rlottie
git clone https://github.com/Samsung/rlottie.git

# Game and tools oriented refactored version of GLU tesselator.
# https://github.com/memononen/libtess2
git clone https://github.com/memononen/libtess2.git

# The fastest and smallest JavaScript polygon triangulation library for your WebGL apps.
# https://github.com/mapbox/earcut
git clone https://github.com/mapbox/earcut.git

# Mesh replacement for THREE.Line. Instead of using GL_LINE, it uses a strip of tiangles billboarded.
# https://github.com/spite/THREE.MeshLine
git clone https://github.com/spite/THREE.MeshLine.git

# libtess
# https://github.com/sdragonx/libtess
git clone https://github.com/sdragonx/libtess.git

# Eigen is a C++ template library for linear algebra: matrices, vectors, numerical solvers, and related algorithms.
# https://gitlab.com/libeigen/eigen
git clone https://gitlab.com/libeigen/eigen.git

# A C header file to help write cross-platform code related to stdio functions
# https://github.com/brackeen/file-compat
git clone https://github.com/brackeen/file-compat.git

# Linux Syscall Support (LSS)
# https://gitee.com/chromiumsrc/linux-syscall-support
git clone https://gitee.com/chromiumsrc/linux-syscall-support.git

# A modern formatting library
# https://github.com/fmtlib/fmt
git clone https://github.com/fmtlib/fmt.git

# Fast C++ logging library.
# https://github.com/gabime/spdlog
git clone https://github.com/gabime/spdlog.git

# TinyXML2 is a simple, small, efficient, C++ XML parser that can be easily integrated into other programs.
# https://github.com/leethomason/tinyxml2
git clone https://github.com/leethomason/tinyxml2.git

# Cross-platform asynchronous I/O
# https://github.com/libuv/libuv
git clone https://github.com/libuv/libuv.git

# MessagePack is an efficient binary serialization format, which lets you exchange data among multiple languages like JSON, except that it's faster and smaller. 
# https://github.com/msgpack/msgpack-c
git clone https://github.com/msgpack/msgpack-c.git

# An open-source C++ library developed and used at Facebook.
# https://chromium.googlesource.com/breakpad/breakpad
git clone https://chromium.googlesource.com/breakpad/breakpad

# An open-source C++ library developed and used at Facebook.
# https://github.com/facebook/folly
git clone https://github.com/facebook/folly.git


# Linux kernel source tree
# https://github.com/torvalds/linux
git clone https://github.com/torvalds/linux.git

# Boost provides free peer-reviewed portable C++ source libraries.
# https://www.boost.org/

################################################################
# iOS
################################################################
# Fast, non-deadlocking parallel object cache for iOS, tvOS and OS X
# https://github.com/pinterest/PINCache
# git clone https://github.com/pinterest/PINCache.git

# Smooth asynchronous user interfaces for iOS apps.
# https://github.com/TextureGroup/Texture
# git clone https://github.com/TextureGroup/Texture.git

################################################################
# tools
################################################################

# A fast build system
# https://github.com/facebook/buck
# git clone https://github.com/facebook/buck.git

# Data Science Using Python
# https://github.com/WillKoehrsen/Data-Analysis
# git clone https://github.com/WillKoehrsen/Data-Analysis.git

# DGraphics API Debugger
# https://github.com/google/gapid
# git clone https://github.com/google/gapid.git

# RenderDoc is a stand-alone graphics debugging tool.
# https://github.com/baldurk/renderdoc
# git clone https://github.com/baldurk/renderdoc.git

# The LLVM Project is a collection of modular and reusable compiler and toolchain technologies.
# https://github.com/llvm/llvm-project
# git clone https://github.com/llvm/llvm-project.git

# A fast, open source web browser engine.
# https://webkit.org
# git clone https://github.com/WebKit/webkit.git

# A fast, open source web browser engine.
# https://github.com/google/sanitizers/wiki/AddressSanitizerHowToBuild
# svn co http://llvm.org/svn/llvm-project/llvm/trunk llvm
# R=$(svn info | grep Revision: | awk '{print $2}') 
# (cd tools && svn co -r $R http://llvm.org/svn/llvm-project/cfe/trunk clang)
# (cd projects && svn co -r $R http://llvm.org/svn/llvm-project/compiler-rt/trunk compiler-rt)
# cmake -DCMAKE_SYSROOT=~/toolchain/arm-2019.09/arm-linux-gnueabi/libc/ -DCMAKE_C_COMPILER_EXTERNAL_TOOLCHAIN=~/toolchain/arm-2019.09 -DCMAKE_ASM_COMPILER_TARGET="arm-linux-gnueabi" -DCMAKE_C_COMPILER_TARGET="arm-linux-gnueabi" -DCMAKE_C_COMPILER=~/toolchain/arm-2019.09/bin/arm-linux-gnueabi-gcc -DCMAKE_CXX_COMPILER=~/toolchain/arm-2019.09/bin/arm-linux-gnueabi-g++ -DLLVM_TARGETS_TO_BUILD=ARM -DLLVM_TARGET_ARCH=ARM -DLLVM_DEFAULT_TARGET_TRIPLE=arm-linux-gnueabi -DCLANG_TABLEGEN=~/llvm_9.0.0/test_llvm/bin/clang-tblgen -DLLVM_TABLEGEN=~/llvm_9.0.0/test_llvm/bin/llvm-tblgen -DCMAKE_CROSSCOMPILING=True -DCMAKE_INSTALL_PREFIX=~/llvm-symbolizer_for_arm -DLLVM_TEMPORARILY_ALLOW_OLD_TOOLCHAIN=true -DCMAKE_BUILD_TYPE=Release -DLLVM_ENABLE_ASSERTIONS=ON ../llvm
# make -j32 llvm-symbolizer

# Googletest - Google Testing and Mocking Framework
# https://github.com/google/googletest
# git clone https://github.com/google/googletest.git

# depot_tools
# https://source.codeaurora.org/quic/lc/chromium/tools/depot_tools
# https://www.cnblogs.com/yemaomao/p/12461055.html
# git clone https://source.codeaurora.org/quic/lc/chromium/tools/depot_tools

# https://source.codeaurora.org/quic/lc/chromium

# busybox
# https://git.busybox.net/busybox
# git clone https://git.busybox.net/busybox


echo "====================== Done ======================"
