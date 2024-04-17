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


