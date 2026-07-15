---
title: Background
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示投影片的背景。
type: docs
url: /zh-hant/com.aspose.slides/background/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有實作的介面：**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

表示投影片的背景。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getType()](#getType--) | 返回背景填充的類型。 |
| [setType(byte value)](#setType-byte-) | 返回背景填充的類型。 |
| [getFillFormat()](#getFillFormat--) | 返回 BackgroundType.OwnBackground 填充的 FillFormat。 |
| [getEffectFormat()](#getEffectFormat--) | 返回 BackgroundType.OwnBackground 填充的 EffectFormat。 |
| [getStyleColor()](#getStyleColor--) | 返回 BackgroundType.Themed 填充的 ColorFormat。 |
| [getStyleIndex()](#getStyleIndex--) | 返回背景主題集合中 BackgroundType.Themed 填充的索引。 |
| [setStyleIndex(int value)](#setStyleIndex-int-) | 返回背景主題集合中 BackgroundType.Themed 填充的索引。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效背景資料。 |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | 返回形狀的父投影片。 |
| [getPresentation()](#getPresentation--) | 返回投影片的父簡報。 |
### getType() {#getType--}
```
public final byte getType()
```

返回背景填充的類型。讀寫 [BackgroundType](../../com.aspose.slides/backgroundtype)。

**返回：**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

返回背景填充的類型。讀寫 [BackgroundType](../../com.aspose.slides/backgroundtype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

返回 BackgroundType.OwnBackground 填充的 FillFormat。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

返回 BackgroundType.OwnBackground 填充的 EffectFormat。唯讀 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**返回：**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

返回 BackgroundType.Themed 填充的 ColorFormat。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

返回背景主題集合中 BackgroundType.Themed 填充的索引。0 表示無填充。1..999 為索引。讀寫 int。

**返回：**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

返回背景主題集合中 BackgroundType.Themed 填充的索引。0 表示無填充。1..999 為索引。讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

取得套用繼承後的有效背景資料。

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


**返回：**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**返回：**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

返回形狀的父投影片。唯讀 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**返回：**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

返回投影片的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回：**
[Presentation](../../com.aspose.slides/presentation)