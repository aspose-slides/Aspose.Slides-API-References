---
title: ICustomXmlPart
second_title: Aspose.Slides for Android via Java API Reference
description: Represents custom xml part.
type: docs
url: /fr/com.aspose.slides/icustomxmlpart/
---
```
public interface ICustomXmlPart
```

Représente une partie xml personnalisée.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Renvoie ou définit les données xml sous forme de chaîne UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Renvoie ou définit les données xml sous forme de chaîne UTF-8. |
| [getXmlData()](#getXmlData--) | Renvoie ou définit les données xml. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Renvoie ou définit les données xml. |
| [getItemId()](#getItemId--) | Spécifie un identifiant unique global (GUID) qui identifie de façon unique une seule partie XML personnalisée dans un document Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Spécifie un identifiant unique global (GUID) qui identifie de façon unique une seule partie XML personnalisée dans un document Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Renvoie la collection de schémas XML associés à la partie XML personnalisée. |
| [remove()](#remove--) | Supprime la partie xml personnalisée de la présentation. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

Renvoie ou définit les données xml sous forme de chaîne UTF-8. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

Renvoie ou définit les données xml sous forme de chaîne UTF-8. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

Renvoie ou définit les données xml. Lecture/écriture byte[].

**Renvoie :**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

Renvoie ou définit les données xml. Lecture/écriture byte[].

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

Spécifie un identifiant unique global (GUID) qui identifie de façon unique une seule partie XML personnalisée dans un document Office Open XML. Lecture seule java.util.UUID.

**Renvoie :**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

Spécifie un identifiant unique global (GUID) qui identifie de façon unique une seule partie XML personnalisée dans un document Office Open XML. Lecture seule java.util.UUID.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

Renvoie la collection de schémas XML associés à la partie XML personnalisée. Lecture seule String[].

**Renvoie :**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

Supprime la partie xml personnalisée de la présentation.