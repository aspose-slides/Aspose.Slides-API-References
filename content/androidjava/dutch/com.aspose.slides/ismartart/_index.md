---
title: ISmartArt
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een SmartArt-diagram voor.
type: docs
url: /nl/com.aspose.slides/ismartart/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Stelt een SmartArt diagram voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Retourneert verzamelingen van alle knooppunten in het SmartArt object. |
| [getNodes()](#getNodes--) | Retourneert verzamelingen van hoofdknopen in het SmartArt object. |
| [getLayout()](#getLayout--) | Retourneer of stel de layout van het SmartArt object in. |
| [setLayout(int value)](#setLayout-int-) | Retourneer of stel de layout van het SmartArt object in. |
| [getQuickStyle()](#getQuickStyle--) | Retourneer of stel de quick style van het SmartArt object in. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Retourneer of stel de quick style van het SmartArt object in. |
| [getColorStyle()](#getColorStyle--) | Retourneer of stel de color style van het SmartArt object in. |
| [setColorStyle(int value)](#setColorStyle-int-) | Retourneer of stel de color style van het SmartArt object in. |
| [isReversed()](#isReversed--) | Retourneer of stel de staat van het SmartArt diagram met betrekking tot (van links naar rechts) LTR of (van rechts naar links) RTL, indien het diagram omkering ondersteunt. |
| [setReversed(boolean value)](#setReversed-boolean-) | Retourneer of stel de staat van het SmartArt diagram met betrekking tot (van links naar rechts) LTR of (van rechts naar links) RTL, indien het diagram omkering ondersteunt. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```


Retourneert verzamelingen van alle knooppunten in het SmartArt object. Alleen-lezen [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Retour:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```


Retourneert verzamelingen van hoofdknopen in het SmartArt object. Alleen-lezen [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Retour:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Retourneer of stel de layout van het SmartArt object in. Lezen/schrijven [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Retour:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```


Retourneer of stel de layout van het SmartArt object in. Lezen/schrijven [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```


Retourneer of stel de quick style van het SmartArt object in. Lezen/schrijven [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Retour:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```


Retourneer of stel de quick style van het SmartArt object in. Lezen/schrijven [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```


Retourneer of stel de color style van het SmartArt object in. Lezen/schrijven [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Retour:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```


Retourneer of stel de color style van het SmartArt object in. Lezen/schrijven [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```


Retourneer of stel de staat van het SmartArt diagram met betrekking tot (van links naar rechts) LTR of (van rechts naar links) RTL, indien het diagram omkering ondersteunt. Lezen/schrijven boolean.

**Retour:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```


Retourneer of stel de staat van het SmartArt diagram met betrekking tot (van links naar rechts) LTR of (van rechts naar links) RTL, indien het diagram omkering ondersteunt. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |