---
title: IBackground
second_title: Aspose.Slides for Android via Java API 参考
description: 表示幻灯片的背景。
type: docs
url: /zh/com.aspose.slides/ibackground/
---
**所有实现的接口：**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

表示幻灯片的背景。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 返回背景填充的类型。 |
| [setType(byte value)](#setType-byte-) | 返回背景填充的类型。 |
| [getFillFormat()](#getFillFormat--) | 返回用于 BackgroundType.OwnBackground 填充的 FillFormat。 |
| [getEffectFormat()](#getEffectFormat--) | 返回用于 BackgroundType.OwnBackground 填充的 EffectFormat。 |
| [getStyleColor()](#getStyleColor--) | 返回用于 BackgroundType.Themed 填充的 ColorFormat。 |
| [getStyleIndex()](#getStyleIndex--) | 返回 BackgroundType.Themed 填充在背景主题集合中的索引。 |
| [setStyleIndex(int value)](#setStyleIndex-int-) | 返回 BackgroundType.Themed 填充在背景主题集合中的索引。 |
| [getEffective()](#getEffective--) | 获取已应用继承的有效背景数据。 |
### getType() {#getType--}
```
public abstract byte getType()
```

返回背景填充的类型。可读写 [BackgroundType](../../com.aspose.slides/backgroundtype)。

**返回：**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

返回背景填充的类型。可读写 [BackgroundType](../../com.aspose.slides/backgroundtype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

返回用于 BackgroundType.OwnBackground 填充的 FillFormat。只读 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

返回用于 BackgroundType.OwnBackground 填充的 EffectFormat。只读 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**返回：**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

返回用于 BackgroundType.Themed 填充的 ColorFormat。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

返回 BackgroundType.Themed 填充在背景主题集合中的索引。0 表示无填充。1..999 为索引。可读写 int。

**返回：**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

返回 BackgroundType.Themed 填充在背景主题集合中的索引。0 表示无填充。1..999 为索引。可读写 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

获取已应用继承的有效背景数据。

**返回：**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).