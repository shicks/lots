# Lots

A preprocessor for [ledger-cli] to make it easier to handle lots and "specific identification" of specific lots for minimizing and maximizing capital gains.

To use, add "; LOTS:..." comments into a normal ledger file, then pipe the ledger through the `lots` script: `lots ledger | ledger -f - balance`.
