add_executable (Rupi
				"main.cpp")

target_link_libraries (Rupi PRIVATE core SDL2-static)
target_link_libraries (Rupi PRIVATE SimpleIni)