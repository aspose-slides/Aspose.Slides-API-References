﻿---
title: last_saved_time property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/documentproperties/last_saved_time/
weight: 280
---


## last_saved_time property
Returns the date a presentation was last modified.
            Values are in UTC.
            Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). 
            Can be changed via DocumentProperties instance returning by method [`IPresentationInfo.read_document_properties`](/slides/python-net/aspose.slides/ipresentationinfo/read_document_properties)
            Please see the example in [`IPresentationInfo.update_document_properties`](/slides/python-net/aspose.slides/ipresentationinfo/update_document_properties) method summary.

### Definition:
```python
@property
def last_saved_time(self):
    ...

@last_saved_time.setter
def last_saved_time(self, value):
    ...
```


### See Also
* class [`DocumentProperties`](/slides/python-net/aspose.slides/documentproperties)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

