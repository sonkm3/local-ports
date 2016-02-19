# local-ports
my local ports repository.

## setup
### edit `/opt/local/etc/macports/sources.conf`
add `file:///full/path/to/local-ports` just before `rsync://rsync.macports.org/release/tarballs/ports.tar [default]`

### at `/full/path/to/local-ports` do `portindex`
