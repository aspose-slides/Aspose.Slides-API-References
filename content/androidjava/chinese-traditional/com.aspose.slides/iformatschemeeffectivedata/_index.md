---
title: IFormatSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 不可變物件，包含實際的格式方案屬性。
type: docs
url: /zh-hant/com.aspose.slides/iformatschemeeffectivedata/
---```
public interface IFormatSchemeEffectiveData
```

不可變物件，包含實際的格式方案屬性。

--------------------

此介面用作 [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) 的一部分。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getFillStyles(Integer styleColor)](#getFillStyles-java.lang.Integer-) | 傳回一個由主題定義的填充樣式集合。 |
| [getLineStyles(Integer styleColor)](#getLineStyles-java.lang.Integer-) | 傳回一個由主題定義的線條樣式集合。 |
| [getEffectStyles(Integer styleColor)](#getEffectStyles-java.lang.Integer-) | 傳回一個由主題定義的效果樣式集合。 |
| [getBackgroundFillStyles(Integer styleColor)](#getBackgroundFillStyles-java.lang.Integer-) | 傳回一個由主題定義的背景填充樣式集合。 |
### getFillStyles(Integer styleColor) {#getFillStyles-java.lang.Integer-}
```
public abstract IFillFormatCollectionEffectiveData getFillStyles(Integer styleColor)
```

傳回一個由主題定義的填充樣式集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| styleColor | java.lang.Integer | Color java.lang.Integer |

**返回值:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - 實際填充格式的集合 [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)
### getLineStyles(Integer styleColor) {#getLineStyles-java.lang.Integer-}
```
public abstract ILineFormatCollectionEffectiveData getLineStyles(Integer styleColor)
```

傳回由主題定義的線條樣式集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| styleColor | java.lang.Integer | Color java.lang.Integer |

**返回值:**
[ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata) - 實際線條格式的集合 [ILineFormatCollectionEffectiveData](../../com.aspose.slides/ilineformatcollectioneffectivedata)
### getEffectStyles(Integer styleColor) {#getEffectStyles-java.lang.Integer-}
```
public abstract IEffectStyleCollectionEffectiveData getEffectStyles(Integer styleColor)
```

傳回由主題定義的效果樣式集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| styleColor | java.lang.Integer | Color java.lang.Integer |

**返回值:**
[IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata) - 實際效果樣式的集合 [IEffectStyleCollectionEffectiveData](../../com.aspose.slides/ieffectstylecollectioneffectivedata)
### getBackgroundFillStyles(Integer styleColor) {#getBackgroundFillStyles-java.lang.Integer-}
```
public abstract IFillFormatCollectionEffectiveData getBackgroundFillStyles(Integer styleColor)
```

傳回由主題定義的背景填充樣式集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| styleColor | java.lang.Integer | Color java.lang.Integer |

**返回值:**
[IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata) - 實際背景填充格式的集合 [IFillFormatCollectionEffectiveData](../../com.aspose.slides/ifillformatcollectioneffectivedata)