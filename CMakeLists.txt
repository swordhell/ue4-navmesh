cmake_minimum_required (VERSION 3.8)
project (ue4-navmesh C CXX)

file(GLOB_RECURSE DIR_SRCS Public/*.cpp Public/*.h Public/*.hpp Public/*.c 
	Private/*.cpp Private/*.h Private/*.hpp Private/*.c )
	
add_library(navmesh ${DIR_SRCS})

