add_library(icmp_chksum icmp_chksum.c)
add_library(geoloc_ip    geoloc_ip.c)
target_link_libraries(geoloc_ip nxjson curl)