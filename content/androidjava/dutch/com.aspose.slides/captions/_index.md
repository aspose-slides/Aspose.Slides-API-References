---
title: Captions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt de WebVTT-ondertiteling voor.
type: docs
url: /nl/com.aspose.slides/captions/
---
**Erfelijkheid:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

Vertegenwoordigt de WebVTT-ondertiteling.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Retourneert de wereldwijd unieke identificatie (GUID) van de ondertiteling. |
| [getLabel()](#getLabel--) | Retourneert of stelt het label van de ondertiteling in. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Retourneert of stelt het label van de ondertiteling in. |
| [getBinaryData()](#getBinaryData--) | Retourneert de binaire gegevens van de ondertiteling. |
| [getDataAsString()](#getDataAsString--) | Retourneert de ondertitelingsgegevens als UTF-8-gecodeerde string Alleen-lezen String. |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```


Retourneert de wereldwijd unieke identificatie (GUID) van de ondertiteling. Alleen-lezen java.util.UUID.

**Retour:**
java.util.UUID
### getLabel() {#getLabel--}
```
public final String getLabel()
```


Retourneert of stelt het label van de ondertiteling in. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```


Retourneert of stelt het label van de ondertiteling in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Retourneert de binaire gegevens van de ondertiteling. Alleen-lezen  byte[] .

**Retour:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```


Retourneert de ondertitelingsgegevens als UTF-8-gecodeerde string Alleen-lezen String.

**Retour:**
java.lang.String