---
title: Convert
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/convert/
---

## Convert class

 Represents a group of methods intended to convert  Presentation.
 
### Convert {#Convert}

| Name | Description |
| --- | --- |
| Convert() |  |

 **Returns:**
Convert


---


### autoByExtension {#autoByExtension}

| Name | Description |
| --- | --- |
| autoByExtension (String, String) | Converts Presentation using the passed output path extension to determine the required export format. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presPath | String | Path of the input presentation |
| outPath | String | Output path |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | If unknown or unsupported format |


---


### toJpeg {#toJpeg}

| Name | Description |
| --- | --- |
| toJpeg ([Presentation](../presentation), String) | Converts the input presentation to a set of JPEG format images. If the output file name is given as "myPath/myFilename.jpeg", the result will be saved as a set of "myPath/myFilename_N.jpeg" files, where N is a slide number. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | The input presentation. |
| outputFileName | String | The output file name. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | null | ArgumentException |


---


### toJpeg {#toJpeg}

| Name | Description |
| --- | --- |
| toJpeg ([Presentation](../presentation), String, Dimension) | Converts the input presentation to a set of JPEG format images. If the output file name is given as "myPath/myFilename.jpeg", the result will be saved as a set of "myPath/myFilename_N.jpeg" files, where N is a slide number. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | The input presentation |
| outputFileName | String | The output file name. |
| imageSize | Dimension | The size of each generated image. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | null | ArgumentException |


---


### toJpeg {#toJpeg}

| Name | Description |
| --- | --- |
| toJpeg ([Presentation](../presentation), String, float, [RenderingOptions](../renderingoptions)) | Converts the input presentation to a set of JPEG format images. If the output file name is given as "myPath/myFilename.jpeg", the result will be saved as a set of "myPath/myFilename_N.jpeg" files, where N is a slide number. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | The input presentation. |
| outputFileName | String | The output file name. |
| scale | float | The scaling factor applied to the output images relative to the original slide size. |
| options | [RenderingOptions](../renderingoptions) | The rendering options. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | null | ArgumentException |


---


### toPdf {#toPdf}

| Name | Description |
| --- | --- |
| toPdf (String, String) | Converts Presentation to PDF. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presPath | String | Path of the input presentation |
| outPath | String | Output path |

 **Returns:**
void


---


### toPdf {#toPdf}

| Name | Description |
| --- | --- |
| toPdf (String, String, [PdfOptions](../pdfoptions)) | Converts Presentation to PDF. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presPath | String | Path of the input presentation |
| outPath | String | Output path |
| options | [PdfOptions](../pdfoptions) | Output PDF options |

 **Returns:**
void


---


### toPdf {#toPdf}

| Name | Description |
| --- | --- |
| toPdf ([Presentation](../presentation), String) | Converts Presentation to PDF. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Input presentation |
| outPath | String | Output path |

 **Returns:**
void


---


### toPdf {#toPdf}

| Name | Description |
| --- | --- |
| toPdf ([Presentation](../presentation), String, [PdfOptions](../pdfoptions)) | Converts Presentation to PDF. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Input presentation |
| outPath | String | Output path |
| options | [PdfOptions](../pdfoptions) | Output PDF options |

 **Returns:**
void


---


### toPng {#toPng}

| Name | Description |
| --- | --- |
| toPng ([Presentation](../presentation), String) | Converts the input presentation to a set of PNG format images. If the output file name is given as "myPath/myFilename.png", the result will be saved as a set of "myPath/myFilename_N.png" files, where N is a slide number. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | The input presentation. |
| outputFileName | String | The output file name. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | null | ArgumentException |


---


### toPng {#toPng}

| Name | Description |
| --- | --- |
| toPng ([Presentation](../presentation), String, Dimension) | Converts the input presentation to a set of PNG format images. If the output file name is given as "myPath/myFilename.png", the result will be saved as a set of "myPath/myFilename_N.png" files, where N is a slide number. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | The input presentation |
| outputFileName | String | The output file name. |
| imageSize | Dimension | The size of each generated image. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | null | ArgumentException |


---


### toPng {#toPng}

| Name | Description |
| --- | --- |
| toPng ([Presentation](../presentation), String, float, [RenderingOptions](../renderingoptions)) | Converts the input presentation to a set of PNG format images. If the output file name is given as "myPath/myFilename.png", the result will be saved as a set of "myPath/myFilename_N.png" files, where N is a slide number. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | The input presentation. |
| outputFileName | String | The output file name. |
| scale | float | The scaling factor applied to the output images relative to the original slide size. |
| options | [RenderingOptions](../renderingoptions) | The rendering options. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | null | ArgumentException |


---


### toSvg {#toSvg}

| Name | Description |
| --- | --- |
| toSvg (String) | Converts Presentation to SVG. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presPath | String | Path of the input presentation |

 **Returns:**
void


---


### toSvg {#toSvg}

| Name | Description |
| --- | --- |
| toSvg (String, [Convert.GetOutPathCallback](../convert.getoutpathcallback)) | Converts Presentation to SVG. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| presPath | String | Path of the input presentation |
| getOutPath | [Convert.GetOutPathCallback](../convert.getoutpathcallback) | Callback that returns the SVG output path for each slide in the presentation |

 **Returns:**
void


---


### toSvg {#toSvg}

| Name | Description |
| --- | --- |
| toSvg ([Presentation](../presentation), [Convert.GetOutPathCallback](../convert.getoutpathcallback)) | Converts Presentation to SVG. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Input presentation |
| getOutPath | [Convert.GetOutPathCallback](../convert.getoutpathcallback) | Callback that returns the SVG output path for each slide in the presentation |

 **Returns:**
void


---


### toSvg {#toSvg}

| Name | Description |
| --- | --- |
| toSvg ([Presentation](../presentation), [SVGOptions](../svgoptions)) | Converts Presentation to SVG. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Input presentation |
| options | [SVGOptions](../svgoptions) | SVG export options |

 **Returns:**
void


---


### toSvg {#toSvg}

| Name | Description |
| --- | --- |
| toSvg ([Presentation](../presentation), [Convert.GetOutPathCallback](../convert.getoutpathcallback), [SVGOptions](../svgoptions)) | Converts Presentation to SVG. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Input presentation |
| getOutPath | [Convert.GetOutPathCallback](../convert.getoutpathcallback) | Callback that returns the SVG output path for each slide in the presentation |
| options | [SVGOptions](../svgoptions) | SVG export options |

 **Returns:**
void


---


### toTiff {#toTiff}

| Name | Description |
| --- | --- |
| toTiff ([Presentation](../presentation), String) | Converts the input presentation to a set of TIFF format images. If the output file name is given as "myPath/myFilename.tiff", the result will be saved as a set of "myPath/myFilename_N.tiff" files, where N is a slide number. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | The input presentation. |
| outputFileName | String | The output file name. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | null | ArgumentException |


---


### toTiff {#toTiff}

| Name | Description |
| --- | --- |
| toTiff ([Presentation](../presentation), String, [TiffOptions](../tiffoptions), boolean) | Converts the input presentation to TIFF format with custom options. If the output file name is given as "myPath/myFilename.tiff" and multipage is false, the result will be saved as a set of "myPath/myFilename_N.tiff" files, where N is a slide number. Otherwise, if multipage is true, the result will be a multi-page "myPath/myFilename.tiff" document. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | The input presentation. |
| outputFileName | String | The output file name. |
| options | [TiffOptions](../tiffoptions) | The TIFF saving options. |
| multipage | boolean | Specifies whether the generated TIFF document should be a multi-page. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | null | ArgumentException |


---


