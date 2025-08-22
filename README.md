# Cloud Projects

## Structure
- dev/: Development environment
- stage/: Staging environment
- prod/: Production environment
- scripts/: Executable automation scripts (restricted access)
- docs/: Documentation (shared access)

## Permissions Policy
- scripts/: 700 (owner only)
- docs/: 755 (readable by group and others)
