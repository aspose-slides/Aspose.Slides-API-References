---
title: get_object_storing_location method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---


## get_object_storing_location {#int-bytes-string-string-string}
Determines where object should be stored.
            This method is called once for each object id.
            It is not guaranteed that there won't be two objects with same data, semanticName and contentType but with different id.

### Returns

Decision



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| id | int | Object id. This id is saving operation-wide unique. |
| entity_data | bytes | Object binary data. This parameter can be null, if object binary data is not generated yet. |
| semantic_name | string | Some short text, describing meaning of object. Controller may use this as a part of external object name, but it is up to dispatcher to ensure that names will be unique and contain only allowed characters. |
| content_type | string | MIME type of object. |
| recomended_extension | string | File name extension, recommended for this MIME type. |



### See Also
* class [`ILinkEmbedController`](/slides/python-net/aspose.slides.export/ilinkembedcontroller)
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)
