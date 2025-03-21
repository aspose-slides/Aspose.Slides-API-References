---
title: XpsOptions
second_title: Aspose.Slides for Java API Reference
description: Provides options that control how a presentation is saved in XPS format.
type: docs
url: /com.aspose.slides/xpsoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Provides options that control how a presentation is saved in XPS format.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // Saving the presentation to XPS document
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // Instantiate the TiffOptions class
>      XpsOptions options = new XpsOptions();
>      // Save MetaFiles as PNG
>      options.setSaveMetafilesAsPng(true);
>      // Save the presentation to XPS document
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Default constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifies whether the generated document should include hidden slides or not. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifies whether the generated document should include hidden slides or not. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True to convert all metafiles used in a presentation to the PNG images. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True to convert all metafiles used in a presentation to the PNG images. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True to draw black frame around each slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True to draw black frame around each slide. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```


Default constructor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Specifies whether the generated document should include hidden slides or not. Default is false.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Specifies whether the generated document should include hidden slides or not. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```


True to convert all metafiles used in a presentation to the PNG images. Read/write boolean.

--------------------

Default is **true**.

**Returns:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```


True to convert all metafiles used in a presentation to the PNG images. Read/write boolean.

--------------------

Default is **true**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```


True to draw black frame around each slide. Read/write boolean.

--------------------

Default is **false**.

**Returns:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```


True to draw black frame around each slide. Read/write boolean.

--------------------

Default is **false**.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

