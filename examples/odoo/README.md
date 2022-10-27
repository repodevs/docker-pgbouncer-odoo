### Odoo with pgBouncer example

This will install:

- PostgreSQL 13
- pgBouncer 1.17.0
- Odoo 14

Usage:

```
docker-compose up -d
```

Watch Logs until Odoo finish installing base module

```
docker-compose logs -f
```

After that open [http://localhost:8069](http://localhost:8069)
