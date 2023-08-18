---
title: IBackground
second_title: Aspose.Slides for Java API Reference
description: Represents background of a slide.
type: docs
url: /com.aspose.slides/ibackground/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

Represents background of a slide.
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Returns a type of background fill. |
| [setType(byte value)](#setType-byte-) | Returns a type of background fill. |
| [getFillFormat()](#getFillFormat--) | Returns a FillFormat for BackgroundType.OwnBackground fill. |
| [getEffectFormat()](#getEffectFormat--) | Returns a EffectFormat for BackgroundType.OwnBackground fill. |
| [getStyleColor()](#getStyleColor--) | Returns a ColorFormat for a BackgroundType.Themed fill. |
| [getStyleIndex()](#getStyleIndex--) | Returns an index of BackgroundType.Themed fill in background theme collection. 0 means no fill. 1..999 - index. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Returns an index of BackgroundType.Themed fill in background theme collection. 0 means no fill. 1..999 - index. |
| [getEffective()](#getEffective--) | Gets effective background data with the inheritance applied. |
### getType() {#getType--}
```
public abstract byte getType()
```


Returns a type of background fill. Read/write [BackgroundType](../../com.aspose.slides/backgroundtype).

**Returns:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Returns a type of background fill. Read/write [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Returns a FillFormat for BackgroundType.OwnBackground fill. Read-only [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```


Returns a EffectFormat for BackgroundType.OwnBackground fill. Read-only [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Returns:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```


Returns a ColorFormat for a BackgroundType.Themed fill. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```


Returns an index of BackgroundType.Themed fill in background theme collection. 0 means no fill. 1..999 - index. Read/write int.

**Returns:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```


Returns an index of BackgroundType.Themed fill in background theme collection. 0 means no fill. 1..999 - index. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```


Gets effective background data with the inheritance applied.

**Returns:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
