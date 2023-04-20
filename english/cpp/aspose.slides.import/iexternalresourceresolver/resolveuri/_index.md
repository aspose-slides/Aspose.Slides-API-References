---
title: ResolveUri()
second_title: Aspose.Slides for C++ API Reference
description: Resolves the absolute URI from the base and relative URIs.
type: docs
weight: 1
url: /cpp/aspose.slides.import/iexternalresourceresolver/resolveuri/
---
## IExternalResourceResolver::ResolveUri(System::String, System::String) method


Resolves the absolute URI from the base and relative URIs.

```cpp
virtual System::String Aspose::Slides::Import::IExternalResourceResolver::ResolveUri(System::String baseUri, System::String relativeUri)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | [System::String](../../../system/string/) | Base URI of linking objects |
| relativeUri | [System::String](../../../system/string/) | Relative URI to the linked object. |

### Return Value

Absolute URI or null if the relative URI cannot be resolved.

## See Also

* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)