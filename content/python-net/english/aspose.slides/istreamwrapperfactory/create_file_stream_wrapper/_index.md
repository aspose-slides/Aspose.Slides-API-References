---
title: create_file_stream_wrapper method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/istreamwrapperfactory/create_file_stream_wrapper/
weight: 10
---


## create_file_stream_wrapper {#str-systemiofilemode}
Creates FileStream with the specified path and creation mode.

### Returns

Stream wrapper for COM interface [`IStreamWrapper`](/slides/python-net/aspose.slides/istreamwrapper)



```python
def create_file_stream_wrapper(self, file_name, file_mode):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_name | **str** | File name **str** |
| file_mode | **System.IO.FileMode** | File mode **System.IO.FileMode** |



## create_file_stream_wrapper {#str-systemiofilemode-systemiofileaccess}
Creates FileStream with the specified path, creation mode, and read/write permission.

### Returns

Stream wrapper for COM interface [`IStreamWrapper`](/slides/python-net/aspose.slides/istreamwrapper)



```python
def create_file_stream_wrapper(self, file_name, file_mode, file_access):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_name | **str** | File name **str** |
| file_mode | **System.IO.FileMode** | File mode **System.IO.FileMode** |
| file_access | **System.IO.FileAccess** | File access **System.IO.FileAccess** |



### See Also
* class [`IStreamWrapper`](/slides/python-net/aspose.slides/istreamwrapper)
* class [`IStreamWrapperFactory`](/slides/python-net/aspose.slides/istreamwrapperfactory)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
