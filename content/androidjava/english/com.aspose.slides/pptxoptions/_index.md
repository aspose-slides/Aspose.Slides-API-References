---
title: PptxOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents options for saving OpenXml presentations PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /com.aspose.slides/pptxoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

Represents options for saving OpenXml presentations (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## Constructors

| Constructor | Description |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | Creates new instance of PptxOptions |
## Methods

| Method | Description |
| --- | --- |
| [getConformance()](#getConformance--) | Specifies the conformance class to which the Presentation document conforms. |
| [setConformance(int value)](#setConformance-int-) | Specifies the conformance class to which the Presentation document conforms. |
| [getZip64Mode()](#getZip64Mode--) | Specifies whether the ZIP64 format is used for the Presentation document. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Specifies whether the ZIP64 format is used for the Presentation document. |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```


Creates new instance of PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```


Specifies the conformance class to which the Presentation document conforms. Default value is [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Returns:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```


Specifies the conformance class to which the Presentation document conforms. Default value is [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
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
public final void setZip64Mode(int value)
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

