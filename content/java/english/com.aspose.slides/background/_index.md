---
title: Background
second_title: Aspose.Slides for Java API Reference
description: Represents background of a slide.
type: docs
url: /com.aspose.slides/background/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

Represents background of a slide.
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Returns a type of background fill. |
| [setType(byte value)](#setType-byte-) | Returns a type of background fill. |
| [getFillFormat()](#getFillFormat--) | Returns a FillFormat for BackgroundType.OwnBackground fill. |
| [getEffectFormat()](#getEffectFormat--) | Returns a EffectFormat for BackgroundType.OwnBackground fill. |
| [getStyleColor()](#getStyleColor--) | Return a ColorFormat for a BackgroundType.Themed fill. |
| [getStyleIndex()](#getStyleIndex--) | Returns an index of BackgroundType.Themed fill in background theme collection. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Returns an index of BackgroundType.Themed fill in background theme collection. |
| [getEffective()](#getEffective--) | Gets effective background data with the inheritance applied. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Returns the parent slide of a shape. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a slide. |
### getType() {#getType--}
```
public final byte getType()
```


Returns a type of background fill. Read/write [BackgroundType](../../com.aspose.slides/backgroundtype).

**Returns:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


Returns a type of background fill. Read/write [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Returns a FillFormat for BackgroundType.OwnBackground fill. Read-only [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```


Returns a EffectFormat for BackgroundType.OwnBackground fill. Read-only [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Returns:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```


Return a ColorFormat for a BackgroundType.Themed fill. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```


Returns an index of BackgroundType.Themed fill in background theme collection. 0 means no fill. 1..999 - index. Read/write int.

**Returns:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```


Returns an index of BackgroundType.Themed fill in background theme collection. 0 means no fill. 1..999 - index. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```


Gets effective background data with the inheritance applied.

--------------------

> ```
> This example demonstrates getting effective background properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IBackgroundEffectiveData effectiveBackground = pres.getSlides().get_Item(0).getBackground().getEffective();
>  	System.out.println("Background fill type: " + effectiveBackground.getFillFormat().getFillType());
>  	System.out.println("Any effects applied: " + !effectiveBackground.getEffectFormat().isNoEffects());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Read-only long.

**Returns:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```


Returns the parent slide of a shape. Read-only [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returns:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```


Returns the parent presentation of a slide. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[Presentation](../../com.aspose.slides/presentation)
