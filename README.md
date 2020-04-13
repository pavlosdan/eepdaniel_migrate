Partial Import:
drush config-import --partial --source=modules/custom/eepdaniel_migrate/config/install/

Delete Configuration:
drush cdel migrate_plus.migrate_group.eepdaniel_articles

Drush commands supported include:
ms  - migrate:status - Lists migrations and their status.
mim - migrate:import - Performs import operations.
migrate:rollback - Performs rollback operations.
migrate:stop - Cleanly stops a running operation.
migrate:reset-status - Sets a migration status to Idle if it's gotten stuck.
migrate:messages - Lists any messages associated with a migration import.
migrate:fields-source - List the fields available for mapping in a source