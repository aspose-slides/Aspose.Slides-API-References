---
title: MakeRelative()
second_title: Aspose.Slides for C++ API Reference
description: Determines the difference between two Uri instances.
type: docs
weight: 365
url: /system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) method


Determines the difference between two [Uri](../) instances.

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The URI to compare to the current URI |

### Return Value

If the hostname and scheme of the URIs represented by the current object and **toUri** are the same, then this method returns a [String](../../string/) that represents a relative [Uri](../), when appended to the current URI instance, yields **toUri**. If the hostname or scheme is different, then this method returns a [String](../../string/) that represents the **uri** parameter.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)