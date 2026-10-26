---
title: IPortionFormat
second_title: Aspose.Slides for Java API 參考
description: 此類別包含文字段落格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/iportionformat/
---
**已實作的介面:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

此類別包含文字段落格式屬性。與 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 不同，此類別的所有屬性皆可寫入。

--------------------

此類別用於回傳和操作針對特定段落定義的文字段落格式屬性。這表示在取得值時不會套用繼承，因此在大多數情況下會取得代表「未定義」的值。

若要取得包括繼承在內的有效格式參數值，必須使用 [getEffective](../../com.aspose.slides/iportionformat\#getEffective) 方法，該方法會回傳一個 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 實例。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Returns or sets bookmark identifier. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Returns or sets bookmark identifier. |
| [getSmartTagClean()](#getSmartTagClean--) | Determines whether the smart tag should be cleaned. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Determines whether the smart tag should be cleaned. |
| [getEffective()](#getEffective--) | Gets effective portion formatting data with the inheritance applied. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


取得或設定書籤識別碼。讀寫 String.

**回傳:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```


取得或設定書籤識別碼。讀寫 String.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


判斷是否應清除智慧標籤。未套用繼承。讀寫 boolean.

**回傳:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```


判斷是否應清除智慧標籤。未套用繼承。讀寫 boolean.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```


取得套用繼承的有效段落格式資料。

**回傳:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).