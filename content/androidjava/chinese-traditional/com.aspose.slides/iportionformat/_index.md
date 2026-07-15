---
title: IPortionFormat
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 此類別包含文字片段的格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/iportionformat/
---
**已實作的介面:**  
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

此類別包含文字片段的格式屬性。與 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 不同，此類別的所有屬性皆可寫入。

--------------------

此類別用於返回與操作針對特定文字片段所定義的格式屬性。這表示在取得值時不會套用繼承，因此在大多數情況下會得到「未定義」的值。

若要取得包含繼承的有效格式參數值，必須使用 [getEffective](../../com.aspose.slides/iportionformat\#getEffective) 方法，該方法會返回一個 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 實例。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | 返回或設定書籤識別碼。 |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | 返回或設定書籤識別碼。 |
| [getSmartTagClean()](#getSmartTagClean--) | 判斷是否應清除智慧標籤。 |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | 判斷是否應清除智慧標籤。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效文字片段格式資料。 |

### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

返回或設定書籤識別碼。讀寫 String。

**返回：**  
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

返回或設定書籤識別碼。讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

判斷是否應清除智慧標籤。未套用繼承。讀寫 boolean。

**返回：**  
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

判斷是否應清除智慧標籤。未套用繼承。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

取得套用繼承後的有效文字片段格式資料。

**返回：**  
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)。