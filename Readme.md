# ECDH

[![Build Status](https://travis-ci.org/tang0th/go-ecdh.svg?branch=master)](https://travis-ci.org/tang0th/go-ecdh)

This is a go implementation of elliptical curve diffie-hellman key exchange method.
It supports the NIST curves (and any curves using the `elliptic.Curve` go interface)
as well as djb's curve25519. 

The library handles generating of keys, generating a shared secret, and the
(un)marshaling of the elliptical curve keys into slices of bytes.

## TODO
 * Improve documentation