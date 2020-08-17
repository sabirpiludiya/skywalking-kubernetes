# skywalking-kubernetes


use skywalking-service-secret or vault to initialize mysql credentials

         - name: SW_STORAGE
           value: mysql
         - name: SW_JDBC_URL
           value: jdbc:mysql://172.17.0.1:3306/skywalking1?autoReconnect=true&useSSL=false
         - name: SW_DATA_SOURCE_USER
           value: {MySQLusername}
         - name: SW_DATA_SOURCE_PASSWORD
           value: {MySQLpassword}
         - name: SW_TELEMETRY
           value: prometheus
