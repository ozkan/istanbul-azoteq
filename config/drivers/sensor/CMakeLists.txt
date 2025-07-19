zephyr_library()

zephyr_library_sources_ifdef(CONFIG_ZMK_SENSOR_TPS65 tps65.c)