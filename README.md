# json-provider-fail

Если обновить версию зависимости с
    implementation 'com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:2.11.4'
    на
    implementation 'com.fasterxml.jackson.jaxrs:jackson-jaxrs-json-provider:2.13.1'
    
то возникает: Caused by: java.lang.ClassNotFoundException: javax.ws.rs.core.NoContentException
