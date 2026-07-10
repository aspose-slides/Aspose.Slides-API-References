---
title: ILegend
second_title: 适用于 Android 的 Aspose.Slides via Java API 参考
description: 表示图表图例属性。
type: docs
url: /zh/com.aspose.slides/ilegend/
---
**所有实现的接口：**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

表示图表图例属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOverlay()](#getOverlay--) | 确定是否允许其他图表元素覆盖图例。 |
| [setOverlay(boolean value)](#setOverlay-boolean-) | 确定是否允许其他图表元素覆盖图例。 |
| [getPosition()](#getPosition--) | 指定图例在图表上的位置。 |
| [setPosition(int value)](#setPosition-int-) | 指定图例在图表上的位置。 |
| [getFormat()](#getFormat--) | 返回图例的格式。 |
| [getEntries()](#getEntries--) | 获取图例条目。 |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


确定是否允许其他图表元素覆盖图例。 可读写 boolean。

**返回值:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


确定是否允许其他图表元素覆盖图例。 可读写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


指定图例在图表上的位置。 X、Y、Width、Height 属性的非 NaN 值会覆盖此属性的效果。 可读写 [LegendPositionType](../../com.aspose.slides/legendpositiontype)。

**返回值:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


指定图例在图表上的位置。 X、Y、Width、Height 属性的非 NaN 值会覆盖此属性的效果。 可读写 [LegendPositionType](../../com.aspose.slides/legendpositiontype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


返回图例的格式。 只读 [IFormat](../../com.aspose.slides/iformat)。

**返回值:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```


获取图例条目。 只读 [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)。

**返回值:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)