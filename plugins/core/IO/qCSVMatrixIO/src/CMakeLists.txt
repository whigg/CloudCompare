
set( CC_PLUGIN_CUSTOM_HEADER_LIST
	${CC_PLUGIN_CUSTOM_HEADER_LIST} 
	${CMAKE_CURRENT_SOURCE_DIR}/CSVMatrixFilter.h
	${CMAKE_CURRENT_SOURCE_DIR}/CSVMatrixOpenDialog.h
	PARENT_SCOPE
)

set( CC_PLUGIN_CUSTOM_SOURCE_LIST
	${CC_PLUGIN_CUSTOM_SOURCE_LIST} 
	${CMAKE_CURRENT_SOURCE_DIR}/CSVMatrixFilter.cpp
	${CMAKE_CURRENT_SOURCE_DIR}/CSVMatrixOpenDialog.cpp
	PARENT_SCOPE
)
