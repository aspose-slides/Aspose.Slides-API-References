---
title: GetUrl()
second_title: Aspose.Slides for C++ API Reference
description: "Returns an URL to an external object. This method always called if ILinkEmbedController::GetObjectStoringLocation returned LinkEmbedDecision::Link and may be called if ILinkEmbedController::GetObjectStoringLocation returned LinkEmbedDecision::Embed but embedding is impossible. Can be called multiple time for same object id."
type: docs
weight: 14
url: /aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) method


Returns an URL to an external object. This method always called if [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) returned [LinkEmbedDecision::Link](../../linkembeddecision/) and may be called if [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) returned [LinkEmbedDecision::Embed](../../linkembeddecision/) but embedding is impossible. Can be called multiple time for same object id.

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| id | **int32_t** | Object id. This id is saving operation-wide unique. |
| referrer | **int32_t** | id of referrencing object or 0, if object is referrenced by the root document. May be used to generate relative link. |

### Return Value

Url of external object or null if this object should be ignored.

## See Also

* Class [String](../../../system/string/)
* Class [ILinkEmbedController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)