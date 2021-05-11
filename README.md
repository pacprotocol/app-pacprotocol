# ledger-app-pac

pacprotocol wallet application for Ledger Nano S and Nano X

This follows the beta specification at https://ledgerhq.github.io/btchip-doc/bitcoin-technical-beta.html - with the regular set of APDUs for standard wallet operations enabled.

To compile and load it on a device, have a look here: https://ledger.readthedocs.io/en/latest/userspace/getting_started.html

Can be tested quickly tested with the Python API at https://github.com/LedgerHQ/btchip-python and Electrum (force noPin = True in getClient in plugins/ledger/ledger.py)

