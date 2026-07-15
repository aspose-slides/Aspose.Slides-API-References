---
title: IDataLabel
second_title: Aspose.Slides for Android via Java API 參考
description: 代表一個系列標籤。
type: docs
url: /zh-hant/com.aspose.slides/idatalabel/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

代表一個系列標籤。
## 方法

| 方法 | 描述 |
| --- | --- |
| [isVisible()](#isVisible--) | False 代表資料標籤不可見（因此所有 Show\*-flags (ShowValue, ...) 皆為 false）。 |
| [hide()](#hide--) | 透過將所有 Show\*-flags (ShowValue, ...) 設為 false 使資料標籤隱藏。 |
| [getDataLabelFormat()](#getDataLabelFormat--) | 傳回資料標籤的格式。 |
| [getValueFromCell()](#getValueFromCell--) | 取得或設定活頁簿資料儲存格。 |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | 取得或設定活頁簿資料儲存格。 |
| [getActualLabelText()](#getActualLabelText--) | 根據 DataLabelFormat 設定或 TextFrameForOverriding.Text 值傳回實際標籤文字。 |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False 代表資料標籤不可見（因此所有 Show\*-flags (ShowValue, ...) 皆為 false）。唯讀 boolean。

--------------------

如果資料標籤可見，可使用 Hide() 方法將其隱藏。但若資料標籤不可見 (IsVisible 為 false)，可透過將 Show\*-flags (ShowValue, ...) 設為 true 使資料標籤可見。

**傳回值：**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


透過將所有 Show\*-flags (ShowValue, ...) 設為 false 使資料標籤隱藏。執行後 IsVisible 會是 false。

--------------------

如果資料標籤不可見 (IsVisible 為 false)，可透過將 Show\*-flags (ShowValue, ...) 設為 true 使資料標籤可見。

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```


傳回資料標籤的格式。唯讀 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**傳回值：**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```


取得或設定活頁簿資料儲存格。當 IDataLabelFormat.ShowLabelValueFromCell 屬性為 true 時套用。

**傳回值：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```


取得或設定活頁簿資料儲存格。當 IDataLabelFormat.ShowLabelValueFromCell 屬性為 true 時套用。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```


傳回根據 DataLabelFormat 設定或 TextFrameForOverriding.Text 值的實際標籤文字。

**傳回值：**
java.lang.String - 實際標籤文字 String