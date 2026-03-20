# ether-database-postgres

PostgreSQL-specific extensions for the Ether database stack, still built on JDBC and the Java standard library.

## Scope

- SQLState classification helpers
- PostgreSQL parameter helpers for `jsonb`, `text[]` and `uuid[]`
- Thin utilities intended to complement `ether-database-core` and `ether-jdbc`

## Notes

- This module is still JDBC-based; it does not introduce a PostgreSQL framework.
- It is the right place for vendor-specific helpers such as `RETURNING`, `jsonb` and array handling.

## Maven

```xml
<dependency>
  <groupId>dev.rafex.ether.database</groupId>
  <artifactId>ether-database-postgres</artifactId>
  <version>8.0.0-SNAPSHOT</version>
</dependency>
```
