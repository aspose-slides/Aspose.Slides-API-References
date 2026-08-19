---
title: ISmartArt
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een SmartArt-diagram voor.
type: docs
url: /nl/com.aspose.slides/ismartart/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Stelt een SmartArt-diagram voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Retourneert collecties van alle knooppunten in SmartArt-object. |
| [getNodes()](#getNodes--) | Retourneert collecties van rootknooppunten in SmartArt-object. |
| [getLayout()](#getLayout--) | Retourneer of stel de indeling van het SmartArt-object. |
| [setLayout(int value)](#setLayout-int-) | Retourneer of stel de indeling van het SmartArt-object. |
| [getQuickStyle()](#getQuickStyle--) | Retourneer of stel de snelle stijl van het SmartArt-object. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Retourneer of stel de snelle stijl van het SmartArt-object. |
| [getColorStyle()](#getColorStyle--) | Retourneer of stel de kleurenstijl van het SmartArt-object. |
| [setColorStyle(int value)](#setColorStyle-int-) | Retourneer of stel de kleurenstijl van het SmartArt-object. |
| [isReversed()](#isReversed--) | Retourneer of stel de status van het SmartArt-diagram met betrekking tot (van links naar rechts) LTR of (van rechts naar links) RTL, als het diagram omkering ondersteunt. |
| [setReversed(boolean value)](#setReversed-boolean-) | Retourneer of stel de status van het SmartArt-diagram met betrekking tot (van links naar rechts) LTR of (van rechts naar links) RTL, als het diagram omkering ondersteunt. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

Retourneert collecties van alle knooppunten in SmartArt-object. Alleen-lezen [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Retourneert:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

Retourneert collecties van rootknooppunten in SmartArt-object. Alleen-lezen [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Retourneert:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

Retourneer of stel de indeling van het SmartArt-object. Lezen/Schrijven [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Retourneert:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

Retourneer of stel de indeling van het SmartArt-object. Lezen/Schrijven [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

Retourneer of stel de snelle stijl van het SmartArt-object. Lezen/Schrijven [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Retourneert:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```

Retourneer of stel de snelle stijl van het SmartArt-object. Lezen/Schrijven [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

Retourneer of stel de kleurenstijl van het SmartArt-object. Lezen/Schrijven [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Retourneert:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

Retourneer of stel de kleurenstijl van het SmartArt-object. Lezen/Schrijven [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

Retourneer of stel de status van het SmartArt-diagram met betrekking tot (van links naar rechts) LTR of (van rechts naar links) RTL, als het diagram omkering ondersteunt. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

Retourneer of stel de status van het SmartArt-diagram met betrekking tot (van links naar rechts) LTR of (van rechts naar links) RTL, als het diagram omkering ondersteunt. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |