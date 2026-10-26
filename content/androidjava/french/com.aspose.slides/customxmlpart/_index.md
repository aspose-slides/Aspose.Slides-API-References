---
title: CustomXmlPart
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une partie XML personnalisée.
type: docs
url: /fr/com.aspose.slides/customxmlpart/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

Représente une partie xml personnalisée.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getXmlData()](#getXmlData--) | Renvoie ou définit les données xml. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Renvoie ou définit les données xml. |
| [getXmlAsString()](#getXmlAsString--) | Renvoie ou définit les données xml au format chaîne UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Renvoie ou définit les données xml au format chaîne UTF-8. |
| [getItemId()](#getItemId--) | Spécifie un identifiant unique global (GUID) qui identifie de manière unique une seule partie XML personnalisée dans un document Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Spécifie un identifiant unique global (GUID) qui identifie de manière unique une seule partie XML personnalisée dans un document Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Renvoie la collection de schémas XML associés à la partie XML personnalisée. |
| [remove()](#remove--) | Supprime la partie xml personnalisée de la présentation. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```


Renvoie ou définit les données xml. Lecture/écriture byte[].

**Renvoie :**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```


Renvoie ou définit les données xml. Lecture/écriture byte[].

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```


Renvoie ou définit les données xml au format chaîne UTF-8. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```


Renvoie ou définit les données xml au format chaîne UTF-8. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getItemId() {#getItemId--}
```
public final UUID getItemId()
```


Spécifie un identifiant unique global (GUID) qui identifie de manière unique une seule partie XML personnalisée dans un document Office Open XML. Lecture seule java.util.UUID.

**Renvoie :**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```


Spécifie un identifiant unique global (GUID) qui identifie de manière unique une seule partie XML personnalisée dans un document Office Open XML. Lecture seule java.util.UUID.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```


Renvoie la collection de schémas XML associés à la partie XML personnalisée. Lecture seule String[].

**Renvoie :**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```


Supprime la partie xml personnalisée de la présentation.