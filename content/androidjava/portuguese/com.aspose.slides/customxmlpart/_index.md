---
title: CustomXmlPart
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa a parte xml personalizada.
type: docs
url: /pt/com.aspose.slides/customxmlpart/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

Representa a parte xml personalizada.
## Métodos

| Método | Descrição |
| --- | --- |
| [getXmlData()](#getXmlData--) | Retorna ou define dados xml. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Retorna ou define dados xml. |
| [getXmlAsString()](#getXmlAsString--) | Retorna ou define dados xml como string UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Retorna ou define dados xml como string UTF-8. |
| [getItemId()](#getItemId--) | Especifica um identificador globalmente único (GUID) que identifica exclusivamente uma única parte XML personalizada dentro de um documento Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Especifica um identificador globalmente único (GUID) que identifica exclusivamente uma única parte XML personalizada dentro de um documento Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Retorna a coleção de esquemas XML que estão associados à parte XML personalizada. |
| [remove()](#remove--) | Remove a parte xml personalizada da apresentação. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```

Retorna ou define dados xml. Leitura/gravação byte[].

**Retorna:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```

Retorna ou define dados xml. Leitura/gravação byte[].

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte[] |  |
### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```

Retorna ou define dados xml como string UTF-8. Leitura/gravação String.

**Retorna:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```

Retorna ou define dados xml como string UTF-8. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getItemId() {#getItemId--}
```
public final UUID getItemId()
```

Especifica um identificador globalmente único (GUID) que identifica exclusivamente uma única parte XML personalizada dentro de um documento Office Open XML. Somente leitura java.util.UUID.

**Retorna:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```

Especifica um identificador globalmente único (GUID) que identifica exclusivamente uma única parte XML personalizada dentro de um documento Office Open XML. Somente leitura java.util.UUID.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```

Retorna a coleção de esquemas XML que estão associados à parte XML personalizada. Somente leitura String[].

**Retorna:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```

Remove a parte xml personalizada da apresentação.