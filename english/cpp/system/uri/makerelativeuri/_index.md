---
title: MakeRelativeUri()
second_title: Aspose.Slides for C++ API Reference
description: Determines the difference between URIs represented by the current and the specified Uri objects.
type: docs
weight: 352
url: /cpp/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\&) method


Determines the difference between URIs represented by the current and the specified [Uri](../) objects.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The comparand |

### Return Value

If the hostname and scheme of the URIs represented by the current object and **toUri** are the same, then this method returns a relative [Uri](../) that, when appended to the current URI instance, yields **toUri**. If the hostname or scheme is different, then this method returns a [Uri](../) object that represents the **uri** parameter.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
