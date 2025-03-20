---
title: IPptxOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents options for saving OpenXml presentations PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /com.aspose.slides/ipptxoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

Represents options for saving OpenXml presentations (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## Methods

| Method | Description |
| --- | --- |
| [getConformance()](#getConformance--) | Specifies the conformance class to which the Presentation document conforms. |
| [setConformance(int value)](#setConformance-int-) | Specifies the conformance class to which the Presentation document conforms. |
| [getZip64Mode()](#getZip64Mode--) | Specifies whether the ZIP64 format is used for the Presentation document. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Specifies whether the ZIP64 format is used for the Presentation document. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Specifies whether the presentation thumbnail will be refreshed. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Specifies whether the presentation thumbnail will be refreshed. |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```


Specifies the conformance class to which the Presentation document conforms. Default value is [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Returns:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```


Specifies the conformance class to which the Presentation document conforms. Default value is [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```


Specifies whether the ZIP64 format is used for the Presentation document. The default value is [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public abstract void setZip64Mode(int value)
```


Specifies whether the ZIP64 format is used for the Presentation document. The default value is [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public abstract boolean getRefreshThumbnail()
```


Specifies whether the presentation thumbnail will be refreshed. Read/write boolean. Default value is **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

When the option value is **true**, the new thumbnail will be generated.

When the option value is **false**, the current thumbnail will be saved as is.

**Returns:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```


Specifies whether the presentation thumbnail will be refreshed. Read/write boolean. Default value is **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

When the option value is **true**, the new thumbnail will be generated.

When the option value is **false**, the current thumbnail will be saved as is.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

