﻿---
title: get_url method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---


## get_url {#int-int}
Returns an URL to an external object.
            This method always called if [`ILinkEmbedController.get_object_storing_location`](/slides/python-net/aspose.slides.export/ilinkembedcontroller/get_object_storing_location) returned [`LinkEmbedDecision.LINK`](/slides/python-net/aspose.slides.export/linkembeddecision/LINK) and may be called if [`ILinkEmbedController.get_object_storing_location`](/slides/python-net/aspose.slides.export/ilinkembedcontroller/get_object_storing_location) returned [`LinkEmbedDecision.EMBED`](/slides/python-net/aspose.slides.export/linkembeddecision/EMBED) but embedding is impossible.
            Can be called multiple time for same object id.

### Returns

Url of external object or None if this object should be ignored.



```python
def get_url(self, id, referrer):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| id | **int** | Object id. This id is saving operation-wide unique. |
| referrer | **int** | id of referrencing object or 0, if object is referrenced by the root document. May be used to generate relative link. |



### See Also
* class [`ILinkEmbedController`](/slides/python-net/aspose.slides.export/ilinkembedcontroller)
* module [`aspose.slides.export`](/slides/python-net/aspose.slides.export)
* library [`Aspose.Slides`](/slides/python-net)

