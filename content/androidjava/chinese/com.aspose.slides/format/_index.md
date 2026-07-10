---
title: Format
second_title: Aspose.Slides for Android via Java API 参考
description: 表示图表格式属性。
type: docs
url: /zh/com.aspose.slides/format/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有实现的接口：**
[com.aspose.slides.IFormat](../../com.aspose.slides/iformat)
```
public final class Format extends PVIObject implements IFormat
```

表示图表格式属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFill()](#getFill--) | 返回图表的填充样式属性。 |
| [getLine()](#getLine--) | 返回图表的线条样式属性。 |
| [getEffect()](#getEffect--) | 返回图表使用的效果。 |
| [getEffect3D()](#getEffect3D--) | 返回图表的 3D 格式。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回：**
long
### getFill() {#getFill--}
```
public final IFillFormat getFill()
```

返回图表的填充样式属性。只读 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getLine() {#getLine--}
```
public final ILineFormat getLine()
```

返回图表的线条样式属性。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffect() {#getEffect--}
```
public final IEffectFormat getEffect()
```

返回图表使用的效果。只读 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**返回：**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getEffect3D() {#getEffect3D--}
```
public final IThreeDFormat getEffect3D()
```

返回图表的 3D 格式。只读 [IThreeDFormat](../../com.aspose.slides/ithreedformat)。

**返回：**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)