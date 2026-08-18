---
title: ICustomXmlPart
second_title: Aspose.Slides for Java API Reference
description: Representa una parte XML personalizada.
type: docs
url: /es/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Representa una parte XML personalizada.
## Métodos

| Método | Descripción |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Devuelve o establece datos xml como cadena UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Devuelve o establece datos xml como cadena UTF-8. |
| [getXmlData()](#getXmlData--) | Devuelve o establece datos xml. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Devuelve o establece datos xml. |
| [getItemId()](#getItemId--) | Especifica un identificador global único (GUID) que identifica de forma única una única parte XML personalizada dentro de un documento Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Especifica un identificador global único (GUID) que identifica de forma única una única parte XML personalizada dentro de un documento Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Devuelve la colección de esquemas XML que están asociados con la parte XML personalizada. |
| [remove()](#remove--) | Elimina la parte XML personalizada de la presentación. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```


Devuelve o establece datos xml como cadena UTF-8. Lectura/escritura String.

**Returns:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```


Devuelve o establece datos xml como cadena UTF-8. Lectura/escritura String.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```


Devuelve o establece datos xml. Lectura/escritura byte[].

**Returns:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```


Devuelve o establece datos xml. Lectura/escritura byte[].

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte[] |  |

### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```


Especifica un identificador global único (GUID) que identifica de forma única una única parte XML personalizada dentro de un documento Office Open XML. Solo lectura java.util.UUID.

**Returns:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```


Especifica un identificador global único (GUID) que identifica de forma única una única parte XML personalizada dentro de un documento Office Open XML. Solo lectura java.util.UUID.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```


Devuelve la colección de esquemas XML que están asociados con la parte XML personalizada. Solo lectura String[].

**Returns:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```


Elimina la parte XML personalizada de la presentación.