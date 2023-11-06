# Tugas2_Big-Data

Pada pengerjaan tugas ini saya memiliki 1 Folder dengan nama HadoopSetup yang terdiri dari Hadoop 3.2.1 dan Sqoop 1.4.7. Setelah melakukan konfigurasi, lakukan :
1. .\start-dfs.cmd untuk mengaktifkan namenode dan datanode
2. ./start-yarn.cmd untuk mengaktifkan Yarn
3. jps untuk melihat apakah sudah aktif
4. Pindah ke folder Sqoop 1.4.7
5. sqoop list-databases --connect jdbc:mysql://localhost/ --username sqoop -P untuk menghubungkan MySQL dengan sqoop
6. sqoop import --connect jdbc:mysql://localhost/tugas2 --username hive --password ******* --table movie_statistic_dataset -m1 untuk mengimport database ke dalam hdfs
