---
title: TryCreate()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a Uri object that represents the specified URI; an argument specifies the URI kind.
type: docs
weight: 508
url: /cpp/system/uri/trycreate/
---
## Uri::TryCreate(const String\&, UriKind, SharedPtr\<Uri\>\&) method


Constructs a [Uri](../) object that represents the specified URI; an argument specifies the URI kind.

```cpp
static bool System::Uri::TryCreate(const String &uriString, UriKind uriKind, SharedPtr<Uri> &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | The string URI to be represented by the object being constructed |
| uriKind | [UriKind](../../urikind/) | Specifies the URI kind |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The output argument that, if the construction succeeds, points to the newly constructed [Uri](../) object on method return |

### Return Value

True if the construction succeeded, otherwise - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const String\&, SharedPtr\<Uri\>\&) method


Constructs an [Uri](../) abject from the specified [Uri](../) object representing the base URI and the string representation of relative URI.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const String &relativeUri, SharedPtr<Uri> &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The base URI |
| relativeUri | const [String](../../string/)\& | The relative URI that is added to the base URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The output argument that, if the construction succeeds, points to the newly constructed [Uri](../) object on method return |

### Return Value

True if the construction succeeded, otherwise - false

## Uri::TryCreate(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, SharedPtr\<Uri\>\&) method


Constructs an [Uri](../) abject from the specified base and relative URIs.

```cpp
static bool System::Uri::TryCreate(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri, SharedPtr<Uri> &result)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The base URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The relative URI that is added to the base URI |
| result | [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The output argument that, if the construction succeeds, points to the newly constructed [Uri](../) object on method return |

### Return Value

True if the construction succeeded, otherwise - false

## See Also

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)