########### install files ###############

INSTALL(DIRECTORY ./ DESTINATION share/${PACKAGE}/textures
        FILES_MATCHING PATTERN "*.png"
        PATTERN "*.svg"
        PATTERN "CMakeFiles" EXCLUDE )


