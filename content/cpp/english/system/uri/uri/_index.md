---
title: Uri()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a Uri object that represents the specified URI.
type: docs
weight: 287
url: /system/uri/uri/
---
## Uri::Uri(const String\&) constructor


Constructs a [Uri](../) object that represents the specified URI.

```cpp
System::Uri::Uri(const String &uriString)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | The string URI to be represented by the object being constructed |

## Uri::Uri(const String\&, bool) constructor


Constructs a [Uri](../) object that represents the specified URI; an argument specifies if the URI should be escaped.

```cpp
System::Uri::Uri(const String &uriString, bool dontEscape)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | The string URI to be represented by the object being constructed |
| dontEscape | **bool** | Specifies if the URI should not be escaped |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&, bool) constructor


Constructs an [Uri](../) abject from the specified [Uri](../) object representing the base URI and the string representation of relative URI; an argument specifies if the URI should be escaped.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri, bool dontEscape)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The base URI |
| relativeUri | const [String](../../string/)\& | The relative URI that is added to the base URI |
| dontEscape | **bool** | Specifies if the URI should not be escaped |

## Uri::Uri(const String\&, UriKind) constructor


Constructs a [Uri](../) object that represents the specified URI; an argument specifies the URI kind.

```cpp
System::Uri::Uri(const String &uriString, UriKind uriKind)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uriString | const [String](../../string/)\& | The string URI to be represented by the object being constructed |
| uriKind | [UriKind](../../urikind/) | Specifies the URI kind |

## Uri::Uri(const SharedPtr\<Uri\>\&, const String\&) constructor


Constructs an [Uri](../) abject from the specified base and relative URIs.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const String &relativeUri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The base URI |
| relativeUri | const [String](../../string/)\& | The relative URI that is added to the base URI |

## Uri::Uri(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) constructor


Constructs an [Uri](../) abject from the specified base and relative URIs.

```cpp
System::Uri::Uri(const SharedPtr<Uri> &baseUri, const SharedPtr<Uri> &relativeUri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The base URI |
| relativeUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | The relative URI that is added to the base URI |

## See Also

* Enum [UriKind](../../urikind/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)