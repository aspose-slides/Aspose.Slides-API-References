---
title: Convert
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/convert/
---

## Convert class

 Represents a group of methods intended to convert  Presentation.
 
| [Convert]() |  |

### Result
Convert


---



## Functions

| Name | Description |
| --- | --- |
| [autoByExtension](String, String) | Converts Presentation using the passed output path extension to determine the required export format. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presPath | String | Path of the input presentation |
| outPath | String | Output path |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | If unknown or unsupported format |


---


| [toPdf](String, String) | Converts Presentation to PDF. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presPath | String | Path of the input presentation |
| outPath | String | Output path |


---


| [toPdf](String, String, [PdfOptions](../pdfoptions)) | Converts Presentation to PDF. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presPath | String | Path of the input presentation |
| outPath | String | Output path |
| options | [PdfOptions](../../pdfoptions) | Output PDF options |


---


| [toPdf]([Presentation](../presentation), String) | Converts Presentation to PDF. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Input presentation |
| outPath | String | Output path |


---


| [toPdf]([Presentation](../presentation), String, [PdfOptions](../pdfoptions)) | Converts Presentation to PDF. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Input presentation |
| outPath | String | Output path |
| options | [PdfOptions](../../pdfoptions) | Output PDF options |


---


| [toSvg](String) | Converts Presentation to SVG. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presPath | String | Path of the input presentation |


---


| [toSvg](String, [Convert.GetOutPathCallback](../convert.getoutpathcallback)) | Converts Presentation to SVG. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presPath | String | Path of the input presentation |
| getOutPath | [Convert.GetOutPathCallback](../../convert.getoutpathcallback) | Callback that returns the SVG output path for each slide in the presentation |


---


| [toSvg]([Presentation](../presentation), [Convert.GetOutPathCallback](../convert.getoutpathcallback)) | Converts Presentation to SVG. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Input presentation |
| getOutPath | [Convert.GetOutPathCallback](../../convert.getoutpathcallback) | Callback that returns the SVG output path for each slide in the presentation |


---


| [toSvg]([Presentation](../presentation), [SVGOptions](../svgoptions)) | Converts Presentation to SVG. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Input presentation |
| options | [SVGOptions](../../svgoptions) | SVG export options |


---


| [toSvg]([Presentation](../presentation), [Convert.GetOutPathCallback](../convert.getoutpathcallback), [SVGOptions](../svgoptions)) | Converts Presentation to SVG. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Input presentation |
| getOutPath | [Convert.GetOutPathCallback](../convert.getoutpathcallback) | Callback that returns the SVG output path for each slide in the presentation |
| options | [SVGOptions](../../svgoptions) | SVG export options |


---


