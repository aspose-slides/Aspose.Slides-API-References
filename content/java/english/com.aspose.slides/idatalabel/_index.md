---
title: IDataLabel
second_title: Aspose.Slides for Java API Reference
description: Represents a series labels.
type: docs
url: /com.aspose.slides/idatalabel/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Represents a series labels.
## Methods

| Method | Description |
| --- | --- |
| [isVisible()](#isVisible--) | False means that data label is not visible (and so all Show\*-flags (ShowValue, ...) are false). |
| [hide()](#hide--) | Make data label hidden by setting all Show\*-flags (ShowValue, ...) to false state. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Returns format of the data label. |
| [getValueFromCell()](#getValueFromCell--) | Gets or sets workbook data cell. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Gets or sets workbook data cell. |
| [getActualLabelText()](#getActualLabelText--) | Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False means that data label is not visible (and so all Show\*-flags (ShowValue, ...) are false). Read-only boolean.

--------------------

If data label is visible you can make it hidden with Hide() method. But if data label is not visible (IsVisible is false) you can make data label visible with setting Show\*-flags (ShowValue, ...) to true state.

**Returns:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Make data label hidden by setting all Show\*-flags (ShowValue, ...) to false state. IsVisible will be false after this.

--------------------

If data label is not visible (IsVisible is false) you can make data label visible with setting Show\*-flags (ShowValue, ...) to true state.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```


Returns format of the data label. Read-only [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Returns:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```


Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true.

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```


Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```


Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value.

**Returns:**
java.lang.String - Actual label text String
