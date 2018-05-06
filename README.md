Config files to be used along with secor setup for azure

Note: Please fill the properties with # TO FILL comment above them

TO run the consumer using your secor jar file (say version 0.26 in out case)-
<code>java -ea  -Dlog4j.configuration=log4j.dev.properties   -Dconfig=secor.prod.properties   -cp secor-0.^C-SNAPSHOT.jar:lib/*   com.pinterest.secor.main.ConsumerMain</code> 
