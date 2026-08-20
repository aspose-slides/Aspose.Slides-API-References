---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides for Java API 參考
description: 包含有效文字部分格式屬性的不可變物件。
type: docs
url: /zh-hant/com.aspose.slides/iportionformateffectivedata/
---
**所有已實作的介面：**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

包含有效文字部分格式屬性的不可變物件。

--------------------

此介面與 [IPortionFormat](../../com.aspose.slides/iportionformat) 介面一起使用，以回傳套用繼承的有效格式值。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | 返回書籤識別碼。 |
| [getHyperlinkClick()](#getHyperlinkClick--) | 返回滑鼠點擊時所定義的超連結。 |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | 返回滑鼠懸停時所定義的超連結。 |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


返回書籤識別碼。唯讀 String。

**返回：**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```


返回滑鼠點擊時所定義的超連結。唯讀 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**返回：**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```


返回滑鼠懸停時所定義的超連結。唯讀 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**返回：**
[IHyperlink](../../com.aspose.slides/ihyperlink)