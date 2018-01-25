# iri-haproxy
Configuration file for load balancing and rate limiting a single or multiple iota iri nodes.

 * Line(s) that may need to be tweaked:
 * Line 79: bind 0.0.0.0:14265 (consider which port you want to use)
 * Line 95: Host:\ ha.iota.fm should be changed to your host
 * Line 115+: Your hosts
 * Line 122: Where to bind your haproxy web interface for monitoring
 * Line 129: Your user/password for web interface for monitoring
