---
title: ITableFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents format of a table.
type: docs
url: /zh-hant/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

表示表格的格式。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returns a table fill properties object. |
| [getTransparency()](#getTransparency--) | Gets or sets the transparency of the fill color. |
| [setTransparency(float value)](#setTransparency-float-) | Gets or sets the transparency of the fill color. |
| [getEffective()](#getEffective--) | Gets effective table formatting properties with inheritance and table styles applied. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


傳回表格填充屬性物件。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


取得或設定填充顏色的透明度。可讀寫  float .

**返回：**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


取得或設定填充顏色的透明度。可讀寫  float .

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


取得套用繼承與表格樣式的有效表格格式屬性。

**返回：**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - 一個 [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata)。