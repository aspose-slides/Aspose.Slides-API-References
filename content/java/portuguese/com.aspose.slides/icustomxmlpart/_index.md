---
title: ICustomXmlPart
second_title: Aspose.Slides for Java API Reference
description: Represents custom xml part.
type: docs
url: /pt/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Representa a parte XML personalizada.
## Métodos

| Method | Description |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Retorna ou define os dados XML como string UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Retorna ou define os dados XML como string UTF-8. |
| [getXmlData()](#getXmlData--) | Retorna ou define os dados XML. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Retorna ou define os dados XML. |
| [getItemId()](#getItemId--) | Especifica um identificador globalmente único (GUID) que identifica de forma única uma única parte XML personalizada dentro de um documento Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Especifica um identificador globalmente único (GUID) que identifica de forma única uma única parte XML personalizada dentro de um documento Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Retorna a coleção de esquemas XML associados à parte XML personalizada. |
| [remove()](#remove--) | Remove a parte XML personalizada da apresentação. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```


Retorna ou define os dados XML como string UTF-8. Leitura/gravação String.

**Retorna:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```


Retorna ou define os dados XML como string UTF-8. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```


Retorna ou define os dados XML. Leitura/gravação byte[].

**Retorna:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```


Retorna ou define os dados XML. Leitura/gravação byte[].

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte[] |  |

### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```


Especifica um identificador globalmente único (GUID) que identifica de forma única uma única parte XML personalizada dentro de um documento Office Open XML. Somente leitura java.util.UUID.

**Retorna:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```


Especifica um identificador globalmente único (GUID) que identifica de forma única uma única parte XML personalizada dentro de um documento Office Open XML. Somente leitura java.util.UUID.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```


Retorna a coleção de esquemas XML associados à parte XML personalizada. Somente leitura String[].

**Retorna:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```


Remove a parte XML personalizada da apresentação.