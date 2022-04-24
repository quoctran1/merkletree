# 2.0.1
- Implements == and hashCode in terms of the root hash
- Add hex rendering of the tree making it JSON serialisable
# 2.0.0
- Remove pedantic and use lints instead
- Updated code style to modern dart
- Upgraded pointycastle and change `sha3` to be `keccak256` as they're not the same, don't produce the same output and the impl. doesn't actually use the current sha3
# 1.0.4
- enforce pedantic lint

# 1.0.3
- fix getProof Bug

# 1.0.2
- Lower meta version to 1.1.6 for Flutter compatibility

# 1.0.1
- Update homepage

# 1.0.0
- Initial Implementation of the Dart Merkle Tree