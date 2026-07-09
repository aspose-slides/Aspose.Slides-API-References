---
title: ICaptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the WebVTT closed captions.
type: docs
url: /fr/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

Représente les sous-titres fermés WebVTT.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Renvoie l'identifiant global unique (GUID) des sous-titres fermés. |
| [getLabel()](#getLabel--) | Renvoie ou définit l'étiquette des sous-titres fermés. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Renvoie ou définit l'étiquette des sous-titres fermés. |
| [getBinaryData()](#getBinaryData--) | Renvoie les données binaires des sous-titres fermés. |
| [getDataAsString()](#getDataAsString--) | Renvoie les données des sous-titres fermés sous forme de chaîne encodée en UTF-8 Lecture seule String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


Renvoie l'identifiant global unique (GUID) des sous-titres fermés. Lecture seule java.util.UUID.

**Renvoie :**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


Renvoie ou définit l'étiquette des sous-titres fermés. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


Renvoie ou définit l'étiquette des sous-titres fermés. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Renvoie les données binaires des sous-titres fermés. Lecture seule byte[].

**Renvoie :**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


Renvoie les données des sous-titres fermés sous forme de chaîne encodée en UTF-8 Lecture seule String.

**Renvoie :**
java.lang.String