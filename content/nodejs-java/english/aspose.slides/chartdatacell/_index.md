---
title: ChartDataCell
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/chartdatacell/
---

## ChartDataCell class

 Represents cell for chart data.
 
| [calculate] ([boolean]) | If the cell contains a formula, the value will be updated base on that formula. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| updateValues | [boolean] | If false, no actual calculation will be performed. Use true for possible exceptions check. |


---


| [getChartDataWorksheet] () | Gets the worksheet. Read-only IChartDataWorksheet. |

### Result
[ChartDataWorksheet]


---


| [getColumn] () | Returns the index of the column of worksheet in which the cell is located. Read-only int. |

### Result
int


---


| [getCustomNumberFormat] () | Gets or sets the custom display format of numbers and dates. If value is empty will be used PresetNumberFormat value. Read/write String. |

### Result
String

### Error

| Error | Condition |
| --- | --- |
 | ArgumentNullException | Thrown if value is null. |


---


| [getFormula] () | Gets or sets the formula in A1-style. |

### Result
String


---


| [getPresetNumberFormat] () | Gets or sets the built-in display format of numbers and dates. Preset number must be in [0..22] or [37..49]. Read/write byte. |

### Result
byte


---


| [getR1C1Formula] () | Gets or sets the formula in R1C1-style. |

### Result
String


---


| [getRow] () | Returns the index of the row of worksheet in which the cell is located. Read-only int. |

### Result
int


---


| [getValue] () | Gets or sets the value of a cell. Read/write Object. |

### Result
Object


---


| [isHidden] () | Determines whether the cell is hidden. Read-only boolean. |

### Result
boolean


---


| [setCustomNumberFormat] ([String]) | Gets or sets the custom display format of numbers and dates. If value is empty will be used PresetNumberFormat value. Read/write String. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentNullException | Thrown if value is null. |


---


| [setFormula] ([String]) | Gets or sets the formula in A1-style. |


---


| [setPresetNumberFormat] ([byte]) | Gets or sets the built-in display format of numbers and dates. Preset number must be in [0..22] or [37..49]. Read/write byte. |


---


| [setR1C1Formula] ([String]) | Gets or sets the formula in R1C1-style. |


---


| [setValue] ([Object]) | Gets or sets the value of a cell. Read/write Object. |


---


