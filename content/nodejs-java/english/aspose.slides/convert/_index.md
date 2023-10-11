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


| [autoByExtension] ([String], [String]) Converts Presentation using the passed output path extension to determine the required export format. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presPath | [String] | Path of the input presentation |
| outPath | [String] | Output path |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | If unknown or unsupported format |


---


| [toPdf] ([String], [String]) Converts Presentation to PDF. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presPath | [String] | Path of the input presentation |
| outPath | [String] | Output path |


---


| [toPdf] ([String], [String], [PdfOptions]) Converts Presentation to PDF. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presPath | [String] | Path of the input presentation |
| outPath | [String] | Output path |
| options | [PdfOptions] | Output PDF options |


---


| [toPdf] ([Presentation], [String]) Converts Presentation to PDF. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation] | Input presentation |
| outPath | [String] | Output path |


---


| [toPdf] ([Presentation], [String], [PdfOptions]) Converts Presentation to PDF. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation] | Input presentation |
| outPath | [String] | Output path |
| options | [PdfOptions] | Output PDF options |


---


| [toSvg] ([String]) Converts Presentation to SVG. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presPath | [String] | Path of the input presentation |


---


| [toSvg] ([String], [Convert.GetOutPathCallback]) Converts Presentation to SVG. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presPath | [String] | Path of the input presentation |
| getOutPath | [Convert.GetOutPathCallback] | Callback that returns the SVG output path for each slide in the presentation |


---


| [toSvg] ([Presentation], [Convert.GetOutPathCallback]) Converts Presentation to SVG. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation] | Input presentation |
| getOutPath | [Convert.GetOutPathCallback] | Callback that returns the SVG output path for each slide in the presentation |


---


| [toSvg] ([Presentation], [SVGOptions]) Converts Presentation to SVG. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation] | Input presentation |
| options | [SVGOptions] | SVG export options |


---


| [toSvg] ([Presentation], [Convert.GetOutPathCallback], [SVGOptions]) Converts Presentation to SVG. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation] | Input presentation |
| getOutPath | [Convert.GetOutPathCallback] | Callback that returns the SVG output path for each slide in the presentation |
| options | [SVGOptions] | SVG export options |


---


