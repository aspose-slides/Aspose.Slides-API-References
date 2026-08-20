---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides for Java API 參考
description: 代表一個管理器，負責保留佔位符的行為，包含所有類型的講義及備註投影片的標頭佔位符。
type: docs
url: /zh-hant/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**所有實作的介面:**  
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)  
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

代表一個管理器，負責保留佔位符的行為，包含所有類型的講義及備註投影片的標頭佔位符。

## 方法

| 方法 | 描述 |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | 獲取指示是否存在標頭佔位符的值。讀取 boolean。 |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | 變更投影片標頭佔位符的可見性。 |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | 設定投影片標頭佔位符的文字。 |

### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```

獲取指示是否存在標頭佔位符的值。讀取 boolean。

**傳回:**  
boolean

### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```

變更投影片標頭佔位符的可見性。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| isVisible | boolean | true - 使標頭佔位符可見，否則 - 隱藏它。 |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```

設定投影片標頭佔位符的文字。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |