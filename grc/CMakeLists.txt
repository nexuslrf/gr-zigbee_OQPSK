file(GLOB yml_files "*.yml")

install(FILES ${yml_files} DESTINATION share/gnuradio/grc/blocks )
