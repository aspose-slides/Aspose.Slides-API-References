---
title: BrowsedByIndividual
second_title: Aspose.Sildes for Java API Reference
description: p
 Browsed by individual window
type: docs
weight: 60
url: /java/com.aspose.slides/browsedbyindividual/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Browsed by individual (window)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Initializes a new instance of the BrowsedByIndividual class. |
| [BrowsedByIndividual(p_CT_ShowInfoBrowseElementData data)](#BrowsedByIndividual-com.aspose.slides.pptxxmlparser.p-CT-ShowInfoBrowseElementData-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Show Scroll Bar in Window |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Show Scroll Bar in Window |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```


Initializes a new instance of the BrowsedByIndividual class.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### BrowsedByIndividual(p_CT_ShowInfoBrowseElementData data) {#BrowsedByIndividual-com.aspose.slides.pptxxmlparser.p-CT-ShowInfoBrowseElementData-}
```
 BrowsedByIndividual(p_CT_ShowInfoBrowseElementData data)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | com.aspose.slides.pptxxmlparser.p_CT_ShowInfoBrowseElementData |  |

### getShowScrollbar() {#getShowScrollbar--}
```
public final boolean getShowScrollbar()
```


Show Scroll Bar in Window

**Returns:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```


Show Scroll Bar in Window

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

