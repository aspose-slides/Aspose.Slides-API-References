---
title: ICaptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the WebVTT closed captions.
type: docs
url: /nl/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

Represents the WebVTT closed captions.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Retourneert de wereldwijd unieke identifier (GUID) van de gesloten ondertitels. |
| [getLabel()](#getLabel--) | Retourneert of stelt het label van de gesloten ondertitels in. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Retourneert of stelt het label van de gesloten ondertitels in. |
| [getBinaryData()](#getBinaryData--) | Retourneert de binaire gegevens van de gesloten ondertitels. |
| [getDataAsString()](#getDataAsString--) | Retourneert de gegevens van de gesloten ondertitels als een UTF-8 gecodeerde string Alleen-lezen String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


Retourneert de wereldwijd unieke identifier (GUID) van de gesloten ondertitels. Alleen-lezen java.util.UUID.

**Retourneert:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


Retourneert of stelt het label van de gesloten ondertitels in. Lezen/schrijven String.

**Retourneert:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


Retourneert of stelt het label van de gesloten ondertitels in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Retourneert de binaire gegevens van de gesloten ondertitels. Alleen-lezen byte[].

**Retourneert:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


Retourneert de gegevens van de gesloten ondertitels als een UTF-8 gecodeerde string Alleen-lezen String.

**Retourneert:**
java.lang.String