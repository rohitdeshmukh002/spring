# spring

this is the commmit and push opertaion

<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE hibernate-configuration PUBLIC 
  "-//Hibernate/Hibernate Configuration DTD 3.0//EN" 
  "http://www.hibernate.org/dtd/hibernate-configuration-3.0.dtd">

<hibernate-configuration>
  <session-factory>
    <property name="connection.driver_class">com.mysql.jdbc.Driver</property>
    
    <property name="connection.url">jdbc:mysql://localhost:3306/management</property>
    <property name="dialect">org.hibernate.dialect.MySQL5Dialect</property>
    <property name="connection.username">root</property>
    <property name="connection.password">rohit</property>
    
    <property name="show_sql">true</property>
    <property name="format_sql">true</property>
    <property name="hbm2ddl.auto">update</property>
   
  </session-factory>
</hibernate-configuration>