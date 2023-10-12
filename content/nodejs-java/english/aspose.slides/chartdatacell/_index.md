---
title: ChartDataCell
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/chartdatacell/
---

## ChartDataCell class

 Represents cell for chart data.
 
| Name | Description |
| --- | --- |
| calculate (boolean) | If the cell contains a formula, the value will be updated base on that formula. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| updateValues | boolean | If false, no actual calculation will be performed. Use true for possible exceptions check. |


---


| Name | Description |
| --- | --- |
| getChartDataWorksheet () | Gets the worksheet. Read-only IChartDataWorksheet. |

### Result
ChartDataWorksheet(../../chartdataworksheet)


---


| Name | Description |
| --- | --- |
| getColumn () | Returns the index of the column of worksheet in which the cell is located. Read-only int. |

### Result
int


---


| Name | Description |
| --- | --- |
| getCustomNumberFormat () | Gets or sets the custom display format of numbers and dates. If value is empty will be used PresetNumberFormat value. Read/write String. |

### Result
String

### Error

| Error | Condition |
| --- | --- |
 | ArgumentNullException | Thrown if value is null. |


---


| Name | Description |
| --- | --- |
| getFormula () | Gets or sets the formula in A1-style. |

### Result
String


---


| Name | Description |
| --- | --- |
| getPresetNumberFormat () | Gets or sets the built-in display format of numbers and dates. Preset number must be in [0..22] or [37..49]. Read/write byte. |

### Result
byte


---


| Name | Description |
| --- | --- |
| getR1C1Formula () | Gets or sets the formula in R1C1-style. |

### Result
String


---


| Name | Description |
| --- | --- |
| getRow () | Returns the index of the row of worksheet in which the cell is located. Read-only int. |

### Result
int


---


| Name | Description |
| --- | --- |
| getValue () | Gets or sets the value of a cell. Read/write Object. |

### Result
Object


---


| Name | Description |
| --- | --- |
| isHidden () | Determines whether the cell is hidden. Read-only boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| setCustomNumberFormat (String) | Gets or sets the custom display format of numbers and dates. If value is empty will be used PresetNumberFormat value. Read/write String. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentNullException | Thrown if value is null. |


---


| Name | Description |
| --- | --- |
| setFormula (String) | Gets or sets the formula in A1-style. |


---


| Name | Description |
| --- | --- |
| setPresetNumberFormat (byte) | Gets or sets the built-in display format of numbers and dates. Preset number must be in [0..22] or [37..49]. Read/write byte. |


---


| Name | Description |
| --- | --- |
| setR1C1Formula (String) | Gets or sets the formula in R1C1-style. |


---


| Name | Description |
| --- | --- |
| setValue (Object) | Gets or sets the value of a cell. Read/write Object. |


---


