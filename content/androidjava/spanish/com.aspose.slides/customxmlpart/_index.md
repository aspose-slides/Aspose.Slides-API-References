---
title: CustomXmlPart
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa una parte XML personalizada.
type: docs
url: /es/com.aspose.slides/customxmlpart/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

Representa una parte XML personalizada.
## Métodos

| Método | Descripción |
| --- | --- |
| [getXmlData()](#getXmlData--) | Devuelve o establece datos xml. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Devuelve o establece datos xml. |
| [getXmlAsString()](#getXmlAsString--) | Devuelve o establece datos xml como cadena UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Devuelve o establece datos xml como cadena UTF-8. |
| [getItemId()](#getItemId--) | Especifica un identificador globalmente único (GUID) que identifica de forma única una única parte XML personalizada dentro de un documento Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Especifica un identificador globalmente único (GUID) que identifica de forma única una única parte XML personalizada dentro de un documento Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Devuelve la colección de esquemas XML que están asociados con la parte XML personalizada. |
| [remove()](#remove--) | Elimina la parte XML personalizada de la presentación. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```


Devuelve o establece datos xml. Lectura/escritura byte[].

**Devuelve:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```


Devuelve o establece datos xml. Lectura/escritura byte[].

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte[] |  |

### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```


Devuelve o establece datos xml como cadena UTF-8. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```


Devuelve o establece datos xml como cadena UTF-8. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getItemId() {#getItemId--}
```
public final UUID getItemId()
```


Especifica un identificador globalmente único (GUID) que identifica de forma única una única parte XML personalizada dentro de un documento Office Open XML. Solo lectura java.util.UUID.

**Devuelve:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```


Especifica un identificador globalmente único (GUID) que identifica de forma única una única parte XML personalizada dentro de un documento Office Open XML. Solo lectura java.util.UUID.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```


Devuelve la colección de esquemas XML que están asociados con la parte XML personalizada. Solo lectura String[].

**Devuelve:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```


Elimina la parte XML personalizada de la presentación.