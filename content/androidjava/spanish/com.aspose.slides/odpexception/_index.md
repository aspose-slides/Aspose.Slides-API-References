---
title: OdpException
second_title: Aspose.Slides para Android mediante la API de Java
description: Representa un tipo de excepción interna estándar.
type: docs
url: /es/com.aspose.slides/odpexception/
---
**Herencia:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception
```
public class OdpException extends System.Exception
```

Representa un tipo de excepción interna estándar.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OdpException()](#OdpException--) | Constructor predeterminado |
| [OdpException(String message)](#OdpException-java.lang.String-) | Constructor que permite agregar un mensaje a esta excepción. |
| [OdpException(String message, RuntimeException exception)](#OdpException-java.lang.String-java.lang.RuntimeException-) | Constructor para una excepción que contiene un mensaje y una excepción incrustada. |
### OdpException() {#OdpException--}
```
public OdpException()
```


Constructor predeterminado

### OdpException(String message) {#OdpException-java.lang.String-}
```
public OdpException(String message)
```


Constructor que permite agregar un mensaje a esta excepción.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | java.lang.String | mensaje |

### OdpException(String message, RuntimeException exception) {#OdpException-java.lang.String-java.lang.RuntimeException-}
```
public OdpException(String message, RuntimeException exception)
```


Constructor para una excepción que contiene un mensaje y una excepción incrustada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | java.lang.String | mensaje |
| exception | java.lang.RuntimeException | excepción original |