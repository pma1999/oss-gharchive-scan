# oss-gharchive-scan

El workflow `GH Archive scan data` consulta GH Archive (vía ClickHouse) y commitea el resultado en `oss_scan/gharchive/` para que el repo privado del barrido OSS lo lea por raw.

- Salud de repos: https://raw.githubusercontent.com/pma1999/oss-gharchive-scan/main/oss_scan/gharchive/salud_repos.tsv
- Issues frescas: https://raw.githubusercontent.com/pma1999/oss-gharchive-scan/main/oss_scan/gharchive/issues_frescas.tsv
- Metadatos: https://raw.githubusercontent.com/pma1999/oss-gharchive-scan/main/oss_scan/gharchive/_meta.txt
