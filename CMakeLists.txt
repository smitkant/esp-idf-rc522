idf_component_register(
    SRCS "rc522.c"
    PRIV_REQUIRES driver esp_timer
    INCLUDE_DIRS "."
)