---
title: LegendEntryProperties
second_title: Aspose.Slides for Android via Java API 参考
description: 表示图表的图例属性。
type: docs
url: /zh/com.aspose.slides/legendentryproperties/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties), com.aspose.slides.IDOMObject
```
public class LegendEntryProperties implements ILegendEntryProperties, IDOMObject
```

表示图表的图例属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTextFormat()](#getTextFormat--) | 返回文本格式。 |
| [getHide()](#getHide--) | 确定图例项是否隐藏。 |
| [setHide(boolean value)](#setHide-boolean-) | 确定图例项是否隐藏。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 返回父图表。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父演示文稿。 |
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


返回文本格式。只读 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**返回:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getHide() {#getHide--}
```
public final boolean getHide()
```


确定图例项是否隐藏。读/写 boolean。

**返回:**
boolean
### setHide(boolean value) {#setHide-boolean-}
```
public final void setHide(boolean value)
```


确定图例项是否隐藏。读/写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


返回 Parent_Immediate 对象。只读 IDOMObject。

**返回:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```


返回父图表。只读 [IChart](../../com.aspose.slides/ichart)。

**返回:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


返回 FillFormat 的父幻灯片。只读 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


返回 FillFormat 的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回:**
[IPresentation](../../com.aspose.slides/ipresentation)