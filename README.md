# Commands
Set environment
source ./local-dev/env.sh

Package helm chart
helm package path/to/chart -d dest/of/tgz

Release and promote to replicated Stable channel
replicated release create --yaml-dir path/to/manifests --lint --promote Stable
