find_package( Boost 1.54 ${SEARCH_PARAMETERS} COMPONENTS
	filesystem
	thread
	date_time
	system
)

compile_project( ${module_name} "*.cpp" "*.h" STATIC libraries Boost )
 