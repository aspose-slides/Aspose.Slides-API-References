---
title: ICustomXmlPart
second_title: Aspose.Slides for Android via Java API Reference
description: Representa parte xml personalizada.
type: docs
url: /pt/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Representa parte xml personalizada.
## Métodos

| Method | Description |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Retorna ou define os dados xml como string UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Retorna ou define os dados xml como string UTF-8. |
| [getXmlData()](#getXmlData--) | Retorna ou define os dados xml. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Retorna ou define os dados xml. |
| [getItemId()](#getItemId--) | Especifica um identificador globalmente único (GUID) que identifica de forma exclusiva uma única parte XML personalizada dentro de um documento Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Especifica um identificador globalmente único (GUID) que identifica de forma exclusiva uma única parte XML personalizada dentro de um documento Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Retorna a coleção de esquemas XML associados à parte XML personalizada. |
| [remove()](#remove--) | Remove a parte xml personalizada da apresentação. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

Retorna ou define os dados xml como string UTF-8. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

Retorna ou define os dados xml como string UTF-8. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

Retorna ou define os dados xml. Leitura/Gravação byte[].

**Retorna:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

Retorna ou define os dados xml. Leitura/Gravação byte[].

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte[] |  |

### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Especifica um identificador globalmente único (GUID) que identifica de forma exclusiva uma única parte XML personalizada dentro de um documento Office Open XML. Somente leitura java.util.UUID.

**Retorna:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Especifica um identificador globalmente único (GUID) que identifica de forma exclusiva uma única parte XML personalizada dentro de um documento Office Open XML. Somente leitura java.util.UUID.

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

Remove a parte xml personalizada da apresentação.