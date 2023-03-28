---
title: ResolveUri()
second_title: Aspose.Slides for C++ API Reference
description: Resolves the absolute URI from the base and relative URIs.
type: docs
weight: 1
url: /cpp/aspose.slides.import/externalresourceresolver/resolveuri/
---
## ExternalResourceResolver::ResolveUri([System::String](../../../system/string/), [System::String](../../../system/string/)) method


Resolves the absolute URI from the base and relative URIs.

```cpp
System::String Aspose::Slides::Import::ExternalResourceResolver::ResolveUri(System::String baseUri, System::String relativeUri) override
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
* Class [ExternalResourceResolver](../)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)
