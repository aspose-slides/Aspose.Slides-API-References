---
title: DataTable
second_title: Aspose.Slides 面向 Android 的 Java API 参考
description: 表示数据表属性。
type: docs
url: /zh/com.aspose.slides/datatable/
---
**继承:**  
java.lang.Object, com.aspose.slides.DomObject

**已实现的所有接口:**  
[com.aspose.slides.IDataTable](../../com.aspose.slides/idatatable)  
```
public class DataTable extends DomObject<Chart> implements IDataTable
```

表示数据表属性。  
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFormat()](#getFormat--) | 返回对象的线条、填充和效果样式。 |
| [hasBorderHorizontal()](#hasBorderHorizontal--) | 如果图表数据表具有水平单元格边框，则为 True。 |
| [setBorderHorizontal(boolean value)](#setBorderHorizontal-boolean-) | 如果图表数据表具有水平单元格边框，则为 True。 |
| [hasBorderOutline()](#hasBorderOutline--) | 如果图表数据表具有轮廓边框，则为 True。 |
| [setBorderOutline(boolean value)](#setBorderOutline-boolean-) | 如果图表数据表具有轮廓边框，则为 True。 |
| [hasBorderVertical()](#hasBorderVertical--) | 如果图表数据表具有垂直单元格边框，则为 True。 |
| [setBorderVertical(boolean value)](#setBorderVertical-boolean-) | 如果图表数据表具有垂直单元格边框，则为 True。 |
| [getShowLegendKey()](#getShowLegendKey--) | 如果数据标签图例键可见，则为 True。 |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | 如果数据标签图例键可见，则为 True。 |
| [getChart()](#getChart--) | 返回图表。 |
| [getTextFormat()](#getTextFormat--) | 返回文本格式。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父演示文稿。 |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

返回对象的线条、填充和效果样式。只读 [IFormat](../../com.aspose.slides/iformat)。

**返回值：**  
[IFormat](../../com.aspose.slides/iformat)
### hasBorderHorizontal() {#hasBorderHorizontal--}
```
public final boolean hasBorderHorizontal()
```

如果图表数据表具有水平单元格边框，则为 True。可读写布尔值。

**返回值：**  
boolean
### setBorderHorizontal(boolean value) {#setBorderHorizontal-boolean-}
```
public final void setBorderHorizontal(boolean value)
```

如果图表数据表具有水平单元格边框，则为 True。可读写布尔值。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### hasBorderOutline() {#hasBorderOutline--}
```
public final boolean hasBorderOutline()
```

如果图表数据表具有轮廓边框，则为 True。可读写布尔值。

**返回值：**  
boolean
### setBorderOutline(boolean value) {#setBorderOutline-boolean-}
```
public final void setBorderOutline(boolean value)
```

如果图表数据表具有轮廓边框，则为 True。可读写布尔值。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### hasBorderVertical() {#hasBorderVertical--}
```
public final boolean hasBorderVertical()
```

如果图表数据表具有垂直单元格边框，则为 True。可读写布尔值。

**返回值：**  
boolean
### setBorderVertical(boolean value) {#setBorderVertical-boolean-}
```
public final void setBorderVertical(boolean value)
```

如果图表数据表具有垂直单元格边框，则为 True。可读写布尔值。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

如果数据标签图例键可见，则为 True。可读写布尔值。

**返回值：**  
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

如果数据标签图例键可见，则为 True。可读写布尔值。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getChart() {#getChart--}
```
public final IChart getChart()
```

返回图表。只读 [IChart](../../com.aspose.slides/ichart)。

**返回值：**  
[IChart](../../com.aspose.slides/ichart)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

返回文本格式。只读 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**返回值：**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回 FillFormat 的父幻灯片。只读 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回值：**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 FillFormat 的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回值：**  
[IPresentation](../../com.aspose.slides/ipresentation)