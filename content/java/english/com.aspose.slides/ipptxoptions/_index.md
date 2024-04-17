---
title: IPptxOptions
second_title: Aspose.Slides for Java API Reference
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

