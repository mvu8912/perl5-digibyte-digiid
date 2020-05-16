Digi-ID implementation in Perl5
===============================

Perl5 implementation of [Digi-ID](https://www.digi-id.io/).

**Digi-ID Open Authentication Protocol**

Pure DigiByte sites and applications shouldn’t have to rely on artificial identification methods such as usernames and passwords. Digi-ID is an open authentication protocol allowing simple and secure authentication using public-key cryptography.

Classical password authentication is an insecure process that could be solved with public key cryptography. The problem however is that it theoretically offloads a lot of complexity and responsibility on the user. Managing private keys securely is complex. However this complexity is already addressed in the DigiByte ecosystem. So doing public key authentication is practically a free lunch to DigiByte users.

**The protocol is based on the following BIP draft:**

https://github.com/bitid/bitid/blob/master/BIP_draft.md

Demo
====

https://digibyteforums.io/ (Has a custom interface on top)

Notes
=====
* Pure Perl5 implementation, no need to run a DigiByte node

Credit
======

Direct Translation from PHP to Perl5 - https://github.com/DigiByte-Core/digiid-php/blob/master/DigiID.php
