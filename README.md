# apt-select
Returns fastest repo servers. Only for Debian/Ubuntu

Usage: apt-select [args..]
 Args:
        -l  --local             Country dependent source list (default)
        -a  --all               Country independent source list
        -s  --servers           Number of mirrors to display (default: 5)
        -v  --verbose           Print debug info
        -t  --threads           Number of threads to use (default: coresX4, overrides threads-max)
        -tm --threads-max       Max number of threads to use (default: 32)
