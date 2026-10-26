---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides for Android via Java API 參考
description: 代表管理員，負責保持占位符的行為，包括所有類型的講義與備註投影片的標題占位符。
type: docs
url: /zh-hant/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**已實作的介面:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

代表管理員，負責保持占位符的行為，包括所有類型的講義與備註投影片的標題占位符。

--------------------

原始介面名稱 "IBaseHandoutNotesSlideHeaderFooterManager" 為了相容於 COM 而被截斷為 "IBaseHandoutNotesSlideHeaderFooterManag"（類型名稱長度必須不超過 39）。
## Methods

| 方法 | 描述 |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | 取得指示是否存在標題占位符的值。 |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | 變更投影片標題占位符的可見性。 |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | 設定投影片標題占位符的文字。 |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

取得指示是否存在標題占位符的值。讀取 boolean。

**傳回:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

變更投影片標題占位符的可見性。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使標題占位符可見，否則 - 隱藏它。 |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

設定投影片標題占位符的文字。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |