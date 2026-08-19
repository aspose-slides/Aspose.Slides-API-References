---
title: ICaptions
second_title: Aspose.Slides for Java API Reference
description: Stelt de WebVTT-ondertitels voor.
type: docs
url: /nl/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

Stelt de WebVTT-ondertitels voor.
## Methoden

| Method | Description |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Geeft de globaal unieke identifier (GUID) van de ondertitels terug. |
| [getLabel()](#getLabel--) | Geeft of stelt het label van de ondertitels in. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Geeft of stelt het label van de ondertitels in. |
| [getBinaryData()](#getBinaryData--) | Geeft de binaire gegevens van de ondertitels terug. |
| [getDataAsString()](#getDataAsString--) | Geeft de ondertitelsgegevens terug als UTF-8 gecodeerde tekenreeks Alleen-lezen String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```

Geeft de globaal unieke identifier (GUID) van de ondertitels terug. Alleen-lezen java.util.UUID.

**Retourneert:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```

Geeft of stelt het label van de ondertitels in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```

Geeft of stelt het label van de ondertitels in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Geeft de binaire gegevens van de ondertitels terug. Alleen-lezen byte[].

**Retourneert:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```

Geeft de ondertitelsgegevens terug als UTF-8 gecodeerde tekenreeks Alleen-lezen String.

**Retourneert:**
java.lang.String