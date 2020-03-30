add_custom_target(check-ch
  COMMAND ${CMAKE_CURRENT_SOURCE_DIR}/runtests.py --test --binary ${CMAKE_BINARY_DIR}/ch
  WORKING_DIRECTORY ${CMAKE_CURRENT_BINARY_DIR}
  USES_TERMINAL
  DEPENDS ch
  )

