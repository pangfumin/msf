add_executable(pose_sensor main.cpp ${CURRENT_HEADERS})

target_link_libraries(pose_sensor pose_distorter ${catkin_LIBRARIES})

add_dependencies(pose_sensor ${${PROJECT_NAME}_EXPORTED_TARGETS})
