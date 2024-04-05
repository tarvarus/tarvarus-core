Tarvarus Core version 0.21.2.1 is now available from:

 <https://download.tarvarus.org/tarvarus-0.21.2.1/>.

This includes a critical bug fix for upgraded wallets to receive via MWEB.

Please report bugs using the issue tracker at GitHub:

  </issues>

To receive security and update notifications, please subscribe to:

  <https://groups.google.com/forum/#!forum/tarvarus-dev>

Notable changes
===============

An issue with MWEB key generation for older wallets that were upgraded was solved.
Keys are now generated from the appropriate keypools, and coins sent to previously generated stealth addresses are recoverable.
Use `rescanblockchain` after upgrading to recover any missing MWEB coins.

