---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective text portion formatting properties.
type: docs
weight: 982
url: /java/com.aspose.slides/iportionformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

Immutable object which contains effective text portion formatting properties.

--------------------

This interface is used together with the [IPortionFormat](../../com.aspose.slides/iportionformat) interface to return effective formatting values with inheritance applied.
## Methods

| Method | Description |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Returns bookmark identifier. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Returns the hyperlink defined for mouse click. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Returns the hyperlink defined for mouse over. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


Returns bookmark identifier. Read-only String.

**Returns:**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```


Returns the hyperlink defined for mouse click. Read-only [IHyperlink](../../com.aspose.slides/ihyperlink).

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```


Returns the hyperlink defined for mouse over. Read-only [IHyperlink](../../com.aspose.slides/ihyperlink).

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
