---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides for Java API 参考
description: 不可变对象，包含有效的文本段落格式属性。
type: docs
url: /zh/com.aspose.slides/iportionformateffectivedata/
---
**所有实现的接口：**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

不可变对象，包含有效的文本段落格式属性。

--------------------

此接口与 [IPortionFormat](../../com.aspose.slides/iportionformat) 接口一起使用，以返回应用继承后的有效格式值。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | 返回书签标识符。 |
| [getHyperlinkClick()](#getHyperlinkClick--) | 返回为鼠标点击定义的超链接。 |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | 返回为鼠标悬停定义的超链接。 |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


返回书签标识符。只读 String。

**返回：**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```


返回为鼠标点击定义的超链接。只读 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**返回：**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```


返回为鼠标悬停定义的超链接。只读 [IHyperlink](../../com.aspose.slides/ihyperlink)。

**返回：**
[IHyperlink](../../com.aspose.slides/ihyperlink)