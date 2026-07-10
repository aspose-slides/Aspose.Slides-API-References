---
title: Background
second_title: Aspose.Slides for Android via Java API 参考
description: 表示幻灯片的背景。
type: docs
url: /zh/com.aspose.slides/background/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有实现的接口：**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

表示幻灯片的背景。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 返回背景填充的类型。 |
| [setType(byte value)](#setType-byte-) | 返回背景填充的类型。 |
| [getFillFormat()](#getFillFormat--) | 返回 BackgroundType.OwnBackground 填充的 FillFormat。 |
| [getEffectFormat()](#getEffectFormat--) | 返回 BackgroundType.OwnBackground 填充的 EffectFormat。 |
| [getStyleColor()](#getStyleColor--) | 返回 BackgroundType.Themed 填充的 ColorFormat。 |
| [getStyleIndex()](#getStyleIndex--) | 返回背景主题集合中 BackgroundType.Themed 填充的索引。 |
| [setStyleIndex(int value)](#setStyleIndex-int-) | 返回背景主题集合中 BackgroundType.Themed 填充的索引。 |
| [getEffective()](#getEffective--) | 获取应用继承后的有效背景数据。 |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | 返回形状的父级幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回幻灯片的父级演示文稿。 |
### getType() {#getType--}
```
public final byte getType()
```


返回背景填充的类型。读/写 [BackgroundType](../../com.aspose.slides/backgroundtype)。

**返回：**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


返回背景填充的类型。读/写 [BackgroundType](../../com.aspose.slides/backgroundtype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


返回 BackgroundType.OwnBackground 填充的 FillFormat。只读 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```


返回 BackgroundType.OwnBackground 填充的 EffectFormat。只读 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**返回：**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```


返回 BackgroundType.Themed 填充的 ColorFormat。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```


返回背景主题集合中 BackgroundType.Themed 填充的索引。0 表示无填充。1..999 为索引。读/写 int。

**返回：**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```


返回背景主题集合中 BackgroundType.Themed 填充的索引。0 表示无填充。1..999 为索引。读/写 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```


获取已应用继承的有效背景数据。

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


返回幻灯片的父级演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回：**
[Presentation](../../com.aspose.slides/presentation)