add_library(
	touch
	STATIC
	include/touch/functions.h
	include/touch/state.h
	include/touch/touch.h
	src/touch.cpp
)

target_include_directories(touch PUBLIC include)
target_link_libraries(touch PUBLIC host)
