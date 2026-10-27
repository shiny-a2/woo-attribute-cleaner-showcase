# Controlled catalog attribute maintenance

Duplicate product attributes can fragment filters and leave old category links pointing at the wrong destination. Cleaning them up requires understanding both taxonomy relationships and variation metadata.

The private maintenance tool starts with an audit. Applying a reviewed plan requires an explicit confirmation. The workflow includes backup checks, ambiguity handling, relationship migration, cache invalidation and redirect handling, so a catalog correction is more deliberate than a database search-and-replace.

For this source publication, the PHP file passed a syntax check and the local Git history passed a secret scan. No cleanup was run against a live store, and no new claim about catalog correctness is made.

Only this summary is public. Catalog exports, migration reports and production configuration are excluded.
