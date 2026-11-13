# Tessellate Labs publication archive

Authoritative machine-readable records for the group's publications.

Layout:

- `catalog.json` - an index with `id`, `title`, `venue`, `year`,
  `published_on` and the ordered contributor names.
- `records/<id>.json` - the full record. `contributors` is an ORDERED array;
  each entry carries `name` and `equal_contribution`. Do not re-sort it.
  `links.record` and `links.brief` are the canonical URLs. `summary` describes
  the work and names the tools that were used.
- `briefs/<id>.pdf` - a one-page brief; its first page repeats the same
  contributor order.

Look a record up by contributor name in `catalog.json`, then open the full
record before citing it. Contributor names are matched by full name; two people
can share a surname.
