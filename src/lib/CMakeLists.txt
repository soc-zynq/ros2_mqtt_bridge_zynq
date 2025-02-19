# Create a library called "ros2_mqtt_bridge_zynq"
add_library(ros2_mqtt_bridge_zynq_lib ros2_mqtt_bridge_zynq.cpp)

# Specify include directories for the library
target_include_directories(ros2_mqtt_bridge_zynq_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
