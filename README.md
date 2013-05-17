STMF-HA
=======

COMSTAR High-Availability tools for Illumos distros

The stmf-ha command provides and manages SCSI Target Mode Framework
(STMF) High-Availaibility mechanisms. STMF is another name for the
Common SCSI Target-Mode Framework (COMSTAR) in Illumos. In essence
what STMF-HA does is provide a method to store and restore COMSTAR 
configuration pertaining to a particular pool on the pool itself. This
makes it possible to easily implement high-available clusters which 
share a single ZFS pool between themselves.

For more information see manpages/stmf-ha.1m in this repository.
