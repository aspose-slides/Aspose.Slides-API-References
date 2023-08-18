---
title: Compare()
second_title: Aspose.Slides for C++ API Reference
description: Compares the specified Uri objects using the specified comparison rules.
type: docs
weight: 521
url: /system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) method


Compares the specified [Uri](../) objects using the specified comparison rules.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The first comparand |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The second comparand |
| partsToCompare | [UriComponents](../../uricomponents/) | Specifies the parts of **uri1** and **uri2** to compare |
| compareFormat | [UriFormat](../../uriformat/) | Specifies the character escaping used when components of URIs are compared |
| comparisonType | [StringComparison](../../stringcomparison/) | One of the StringComparison values |

### Return Value

A negative value if **uri1** is less than **uri2**; 0 if uri1 and uri2 are equal; a positive value if **uri1** is greater than **uri2**

## See Also

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)