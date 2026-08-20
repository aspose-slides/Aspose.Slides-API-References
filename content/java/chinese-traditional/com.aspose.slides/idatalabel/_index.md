---
title: IDataLabel
second_title: Aspose.Slides for Java API 參考
description: 表示一系列標籤。
type: docs
url: /zh-hant/com.aspose.slides/idatalabel/
---
**所有已實作的介面：**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

表示一系列標籤。
## 方法

| 方法 | 說明 |
| --- | --- |
| [isVisible()](#isVisible--) | False 表示資料標籤不可見（因此所有 Show*-flags（ShowValue，...）皆為 false）。 |
| [hide()](#hide--) | 透過將所有 Show*-flags（ShowValue，...）設定為 false 狀態，使資料標籤隱藏。 |
| [getDataLabelFormat()](#getDataLabelFormat--) | 傳回資料標籤的格式。 |
| [getValueFromCell()](#getValueFromCell--) | 取得或設定工作簿資料儲存格。 |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | 取得或設定工作簿資料儲存格。 |
| [getActualLabelText()](#getActualLabelText--) | 根據 DataLabelFormat 設定或 TextFrameForOverriding.Text 值傳回實際標籤文字。 |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False 表示資料標籤不可見（因此所有 Show*-flags（ShowValue，...）皆為 false）。**唯讀** 布林值。

--------------------

如果資料標籤可見，您可以使用 Hide() 方法將其隱藏。但如果資料標籤不可見（IsVisible 為 false），則可透過將 Show*-flags（ShowValue，...）設定為 true 狀態，使資料標籤可見。

**傳回：**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

透過將所有 Show*-flags（ShowValue，...）設定為 false 狀態，使資料標籤隱藏。執行後 IsVisible 會是 false。

--------------------

如果資料標籤不可見（IsVisible 為 false），則可透過將 Show*-flags（ShowValue，...）設定為 true 狀態，使資料標籤可見。

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

傳回資料標籤的格式。**唯讀** [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**傳回：**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

取得或設定工作簿資料儲存格。若 IDataLabelFormat.ShowLabelValueFromCell 屬性為 true，則套用此設定。

**傳回：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

取得或設定工作簿資料儲存格。若 IDataLabelFormat.ShowLabelValueFromCell 屬性為 true，則套用此設定。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

根據 DataLabelFormat 設定或 TextFrameForOverriding.Text 值傳回實際標籤文字。

**傳回：**
java.lang.String - 實際標籤文字字串