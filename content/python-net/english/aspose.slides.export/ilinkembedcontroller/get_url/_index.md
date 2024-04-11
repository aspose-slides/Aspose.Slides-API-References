---
title: get_url method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docS
url: /aspose.slides.export/ilinkembedcontroller/get_url/
weight: 30
---


## get_url {#int-int}
Returns an URL to an external object.
            This method always called if Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste. returned [`LinkEmbedDecision.LINK`](/slides/python-net/aspose.slides.export/linkembeddecision#LINK) and may be called if Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste. returned [`LinkEmbedDecision.EMBED`](/slides/python-net/aspose.slides.export/linkembeddecision#EMBED) but embedding is impossible.
            Can be called multiple time for same object id.

### Returns

Url of external object or null if this object should be ignored.



```python
def get_url(self, id, referrer):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| id | int | Object id. This id is saving operation-wide unique. |
| referrer | int | id of referrencing object or 0, if object is referrenced by the root document. May be used to generate relative link. |



