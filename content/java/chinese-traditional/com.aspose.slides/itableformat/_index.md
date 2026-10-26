---
title: ITableFormat
second_title: Aspose.Slides for Java API Reference
description: 表示表格的格式。
type: docs
url: /zh-hant/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

表示表格的格式。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 傳回表格填充屬性物件。 |
| [getTransparency()](#getTransparency--) | 取得或設定填充顏色的透明度。 |
| [setTransparency(float value)](#setTransparency-float-) | 取得或設定填充顏色的透明度。 |
| [getEffective()](#getEffective--) | 取得套用繼承與表格樣式後的有效表格格式屬性。 |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

傳回表格填充屬性物件。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**傳回：**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

取得或設定填充顏色的透明度。讀寫  float 。

**傳回：**
float

### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

取得或設定填充顏色的透明度。讀寫  float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```

取得套用繼承與表格樣式後的有效表格格式屬性。

**傳回：**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).