---
title: PortionFormat
second_title: Aspose.Sildes for Java API Reference
description: p
 This class contains the text portion formatting properties.
type: docs
weight: 429
url: /java/com.aspose.slides/portionformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**All Implemented Interfaces:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public class PortionFormat extends BasePortionFormat implements IPortionFormat
```

This class contains the text portion formatting properties. Unlike [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), all properties of this class are writeable.

--------------------

This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".

In order to get the effective formatting parameter values including inherited you need to use [PortionFormat\#getEffective](../../com.aspose.slides/portionformat\#getEffective) method which returns a [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) instance.
## Constructors

| Constructor | Description |
| --- | --- |
| [PortionFormat(IDOMObject parentImmediate)](#PortionFormat-com.aspose.slides.IDOMObject-) |  |
| [PortionFormat()](#PortionFormat--) | Initializes a new instance of [PortionFormat](../../com.aspose.slides/portionformat) class. |
## Methods

| Method | Description |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Returns or sets bookmark identifier. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Returns or sets bookmark identifier. |
| [getSmartTagClean()](#getSmartTagClean--) | Determines whether the smart tag should be cleaned. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Determines whether the smart tag should be cleaned. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Returns or sets the hyperlink defined for mouse click. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Returns or sets the hyperlink defined for mouse click. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Returns or sets the hyperlink defined for mouse over. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Returns or sets the hyperlink defined for mouse over. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Hyperlinks manager. |
| [getEffective()](#getEffective--) | Gets effective portion formatting data with the inheritance applied. |
### PortionFormat(IDOMObject parentImmediate) {#PortionFormat-com.aspose.slides.IDOMObject-}
```
 PortionFormat(IDOMObject parentImmediate)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | com.aspose.slides.IDOMObject |  |

### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```


Initializes a new instance of [PortionFormat](../../com.aspose.slides/portionformat) class.

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```


Returns or sets bookmark identifier. Read/write String.

**Returns:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```


Returns or sets bookmark identifier. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```


Determines whether the smart tag should be cleaned. No inheritance applied. Read/write \`\`\` boolean \`\`\`.

**Returns:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```


Determines whether the smart tag should be cleaned. No inheritance applied. Read/write \`\`\` boolean \`\`\`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```


Returns or sets the hyperlink defined for mouse click. Read/write [IHyperlink](../../com.aspose.slides/ihyperlink).

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```


Returns or sets the hyperlink defined for mouse click. Read/write [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```


Returns or sets the hyperlink defined for mouse over. Read/write [IHyperlink](../../com.aspose.slides/ihyperlink).

**Returns:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```


Returns or sets the hyperlink defined for mouse over. Read/write [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```


Hyperlinks manager. Read-only [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Returns:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```


Gets effective portion formatting data with the inheritance applied.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../com.aspose.slides/iportionformateffectivedata).
