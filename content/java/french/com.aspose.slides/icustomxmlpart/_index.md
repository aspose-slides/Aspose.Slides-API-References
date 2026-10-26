---
title: ICustomXmlPart
second_title: Aspose.Slides for Java API Reference
description: Représente une partie XML personnalisée.
type: docs
url: /fr/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

Représente une partie XML personnalisée.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Renvoie ou définit les données XML sous forme de chaîne UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Renvoie ou définit les données XML sous forme de chaîne UTF-8. |
| [getXmlData()](#getXmlData--) | Renvoie ou définit les données XML. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Renvoie ou définit les données XML. |
| [getItemId()](#getItemId--) | Spécifie un identifiant global unique (GUID) qui identifie de manière unique une seule partie XML personnalisée dans un document Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Spécifie un identifiant global unique (GUID) qui identifie de manière unique une seule partie XML personnalisée dans un document Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Renvoie la collection de schémas XML associés à la partie XML personnalisée. |
| [remove()](#remove--) | Supprime la partie XML personnalisée de la présentation. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

Renvoie ou définit les données XML sous forme de chaîne UTF-8. Lecture/écriture String.

**Returns:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

Renvoie ou définit les données XML sous forme de chaîne UTF-8. Lecture/écriture String.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

Renvoie ou définit les données XML. Lecture/écriture byte[].

**Returns:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

Renvoie ou définit les données XML. Lecture/écriture byte[].

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Spécifie un identifiant global unique (GUID) qui identifie de manière unique une seule partie XML personnalisée dans un document Office Open XML. Lecture seule java.util.UUID.

**Returns:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Spécifie un identifiant global unique (GUID) qui identifie de manière unique une seule partie XML personnalisée dans un document Office Open XML. Lecture seule java.util.UUID.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Renvoie la collection de schémas XML associés à la partie XML personnalisée. Lecture seule String[].

**Returns:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

Supprime la partie XML personnalisée de la présentation.