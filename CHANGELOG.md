# scene-subtree-mover

## 1.1.1

### Patch Changes

- df3258e: Refuse an index with an unquoted whole number above 2^53 in its frontmatter, because the YAML write would silently change that value.

## 1.1.0

### Minor Changes

- 605471f: Add free moves between parent groups with a complete subtree preview and source backup.
