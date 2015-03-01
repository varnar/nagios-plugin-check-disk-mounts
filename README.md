nagios-plugin-check-disk-mounts
===============================

`check_disk_mounts` is a Nagios Monitoring Plugin to Check Free Space for Mounted Disks.

This plugin checks all available mount points using Nagios Plugin `check_disk`.

This plugin makes available mount disk mounts without changing any configuration
on Nagios Server or Client.

Disks are fetched from `/etc/mtab`.

syntax:

check_disk_mounts $free_disk_space_warning_threshold $free_disk_space_critical_threshold


## TODO:

- Check for Platform and combine to one script
- fix perf data

## License

<pre>
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
</pre>

