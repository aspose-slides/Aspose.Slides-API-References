---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides for Android via Java API 參考
description: 不可變的物件，包含有效文字部份的格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/iportionformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

不可變的物件，包含有效文字部份格式屬性。

--------------------

此介面與 [IPortionFormat](../../com.aspose.slides/iportionformat) 介面一起使用，以返回套用繼承的有效格式值。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | 傳回書籤識別碼。 |
| [getHyperlinkClick()](#getHyperlinkClick--) | 傳回為滑鼠點擊所定義的超連結。 |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | 傳回為滑鼠移過時所定義的超連結。 |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


傳回書籤識別碼。唯讀 String。

**傳回值：**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```


傳回為滑鼠點擊所定義的超連結。唯讀 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**傳回值：**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```


傳回為滑鼠移過時所定義的超連結。唯讀 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**傳回值：**
[IHyperlink](../../com.aspose.slides/ihyperlink)