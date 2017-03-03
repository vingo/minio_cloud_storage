windows platform:
accessKey : F9VG28ZHDXMN033TUUA6
secretKey : qVQi9Nodi6rUmZoAxt8w5P1B3PxsHD6StNSLZJNK
1. minio.exe server D:\Photos    #setup store directory and start server


mc client command
mc set config  add {alias} http://localhost:9999 {accessKey} {secretKey}   
mc ls {alias}
mc mb {alias}/{bucket_name}
mc --debug ls  {alias}
mc --json ls {alias}
mc cat {alias}{file_name}
mc cp {local_file_name} {alias}/{file_name}  
mc rm {alias}/{file_name}  




