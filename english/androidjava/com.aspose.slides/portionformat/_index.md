---
title: PortionFormat
second_title: Aspose.Slides for Android via Java API Reference
description: This class contains the text portion formatting properties.
type: docs
weight: 431
url: /androidjava/com.aspose.slides/portionformat/
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

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //Instantiate a presentation object that represents a presentation file
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides uses these special identifiers (similar to those used in PowerPoint):
>      // +mn-lt - Body Font Latin (Minor Latin Font)
>      // +mj-lt -Heading Font Latin (Major Latin Font)
>      // +mn-ea - Body Font East Asian (Minor East Asian Font)
>      // +mj-ea - Body Font East Asian (Minor East Asian Font)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".

In order to get the effective formatting parameter values including inherited you need to use [getEffective](../../com.aspose.slides/portionformat\#getEffective) method which returns a [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) instance.
## Constructors

| Constructor | Description |
| --- | --- |
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


Determines whether the smart tag should be cleaned. No inheritance applied. Read/write  boolean .

**Returns:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```


Determines whether the smart tag should be cleaned. No inheritance applied. Read/write  boolean .

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
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
