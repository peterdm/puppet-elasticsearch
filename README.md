# puppet-elasticsearch
================

Install elasticsearch service

# REQUIREMENTS

* Puppet >=2.6 if using parameterized classes

# Dependencies

# [stdlib](https://github.com/puppetlabs/puppetlabs-stdlib)
# [Oracle Java 6](http://java.sun.com/javase/downloads/index.jsp) try using the NeSI [oab-java module](https://github.com/nesi/puppet-oabjava)

# Installation

Clone or submodule this repository into:

/etc/puppet/modules/elasticsearch

# Invocation

To install on a node:

include elasticsearch

# Issues

Originally this installs elasticsearch from tarballs, which was bloated the git repository. It should now grab ElasticSearch directly from github, though getting elasticsearch as a package would be ideal.

# References

* ElasticSearch homepage: http://www.elasticsearch.org/

# Attribution

This module is derived from the puppet-blank module by Aaron Hicks (aethylred@gmail.com)

* https://github.com/Aethylred/puppet-blank

This module has been developed for the use with Open Source Puppet (Apache 2.0 license) for automating server & service deployment.

* http://puppetlabs.com/puppet/puppet-open-source/

# Gnu General Public License

This file is part of the blank Puppet module.

The blank Puppet module is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

The blank Puppet module is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with the blank Puppet module.  If not, see <http://www.gnu.org/licenses/>.