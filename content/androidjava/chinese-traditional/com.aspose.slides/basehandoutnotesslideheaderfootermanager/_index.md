---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides for Android via Java API 參考
description: 代表管理員，保留占位符的行為，包括所有類型講義與備註投影片的標題佔位符。
type: docs
url: /zh-hant/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**繼承：**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**已實作的介面：**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

代表管理員，保留占位符的行為，包括所有類型講義與備註投影片的標題佔位符。

## 方法

| 方法 | 描述 |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | 取得指示有標題佔位符的值。讀取布林值。 |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | 變更投影片標題佔位符的可見性。 |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | 設定投影片標題佔位符的文字。 |
### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```

取得指示有標題佔位符的值。讀取布林值。

**回傳值：**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```

變更投影片標題佔位符的可見性。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| isVisible | boolean | true - 使標題佔位符可見，否則 - 隱藏它。 |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```

設定投影片標題佔位符的文字。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要設定的文字。 |