##Oracle SQL Scripts
- active.sql - List active sessions in the database
- awr_snap.sql - Take AWR snapshot
- balance.sql - Show RAC balance
- cre_idx.sql - Generate creation script for an index
- cre_table.sql - Generate creation script for a table
- cre_tablespace.sql - Generate creation script for a tablespace
- cre_user.sql - Generate creation script for a user.  Includes object and system grants
- cre_view.sql - Generate creation script for a view
- datafiles.sql - List datafiles and their status
- db_characterset.sql - Database characterset value
- db_components.sql - List installed components and their current status
- db_links.sql - List database links
- dgPerf.sql - ASM diskgroup performance
- dirs.sql - List database directories
- dplan.sql - Show explain plan for a sql_id
- dplan_awr.sql - Show explain plan for a sql_id from AWR
- find_bind.sql - Find bind variables for a sql_id
- find_bind_awr.sql - Find bind variables from AWR for a sql_id
- find_library_cache_pin.sql - Which objects has library cache pin contention
- find_sql.sql - Find sql based on sql_id or sql text
- find_sql_awr.sql - Find sql in AWR based on sql_id or sql text
- fulltext.sql - Get full sql text for a given sql_id
- io_calibrate.sql - Disk calibration for an ASM diskgroup
- kill_dash.sql - Kill hung dashing queries
- long_ops.sql - Monitor long running queries
- maxshrink.sql - Shrink datafiles to reclaim disk space
- my_sid.sql - What's my SID
- rman_stat.sql - Status of an RMAN job including % complete
- sbl_alter_sessions.sql - Alter session statements for tuning Siebel queries
- schema_size.sql - Total size for a database schema
- slow.sql - Slowest running sql statements from the past X days
- slow_total.sql - Most time consuming sql from the past X days
- stale_stats.sql- List tables and indexes with stale stats
- status.sql - Current instance status
- table_size.sql - Show table size
- tablespace_size.sql - Tablespace current size and free space
- tbsp_usage_history.sql - Historical tablespace usage
- temp_usage.sql - Amount of temporary tablespace used by active sessions.
- topWaits.sql - Top wait events
- topWaitsRac.sql - Top wait events for a RAC database
- top_reads.sql - List objects with the most reads
- unstable_plans.sql - Find sql with changing plans
- user_lock.sql - Find who is locking a user with failed login attempts
- workload_stats.sql - Gather workload statistics