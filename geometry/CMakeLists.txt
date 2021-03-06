project(geometry)

set(
  SRC
  algorithm.cpp
  algorithm.hpp
  angles.cpp
  angles.hpp
  any_rect2d.hpp
  avg_vector.hpp
  cellid.hpp
  clipping.cpp
  clipping.hpp
  covering.hpp
  covering_utils.hpp
  distance.hpp
  distance_on_sphere.cpp
  distance_on_sphere.hpp
  latlon.cpp
  latlon.hpp
  mercator.cpp
  mercator.hpp
  packer.cpp
  packer.hpp
  point2d.hpp
  pointu_to_uint64.hpp
  polygon.hpp
  polyline2d.hpp
  rect2d.hpp
  rect_intersect.hpp
  region2d.hpp
  robust_orientation.cpp
  robust_orientation.hpp
  screenbase.cpp
  screenbase.hpp
  segment2d.cpp
  segment2d.hpp
  simplification.hpp
  spline.cpp
  spline.hpp
  transformations.hpp
  tree4d.hpp
  triangle2d.cpp
  triangle2d.hpp

  region2d/binary_operators.cpp
  region2d/binary_operators.hpp
  region2d/boost_concept.hpp
)

add_library(${PROJECT_NAME} ${SRC})

add_subdirectory(geometry_tests)
