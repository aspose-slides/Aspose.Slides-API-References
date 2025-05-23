﻿---
title: print method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/presentation/print/
weight: 80
---


## print {#}
Prints the whole presentation to the default printer.


```python
def print(self):
    ...
```


### Examples

The following example shows how to set print options Dynamically for a PowerPoint Presentation.


## print {#asposepydrawingprintingprintersettings}
Prints the presentation according to the specified printer settings,
            using the standard (no User Interface) print controller.


```python
def print(self, printer_settings):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| printer_settings | **aspose.pydrawing.Printing.PrinterSettings** | The .NET printer settings to use. |


## print {#str}
Print the whole presentation to the specified printer,
            using the standard (no User Interface) print controller.


```python
def print(self, printer_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| printer_name | **str** | The name of the printer. |


## print {#asposepydrawingprintingprintersettings-str}
Prints the document according to the specified printer settings, using
            the standard (no User Interface) print controller and a presentation name.


```python
def print(self, printer_settings, pres_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| printer_settings | **aspose.pydrawing.Printing.PrinterSettings** | The .NET printer settings to use. |
| pres_name | **str** | The presentation name to display (for example, in a print<br/><br/>            status dialog box or printer queue) while printing the presentation. |



### See Also
* class [`Presentation`](/slides/python-net/aspose.slides/presentation)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

