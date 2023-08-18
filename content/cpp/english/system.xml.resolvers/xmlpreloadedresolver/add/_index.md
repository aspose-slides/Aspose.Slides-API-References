---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds a byte array to the XmlPreloadedResolver store and maps it to a URI. If the store already contains a mapping for the same URI, the existing mapping is overridden.
type: docs
weight: 79
url: /system.xml.resolvers/xmlpreloadedresolver/add/
---
## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&) method


Adds a byte array to the [XmlPreloadedResolver](../) store and maps it to a URI. If the store already contains a mapping for the same URI, the existing mapping is overridden.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | The URI of the data that is being added to the [XmlPreloadedResolver](../) store. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A byte array with the data that corresponds to the provided URI. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Adds a byte array to the [XmlPreloadedResolver](../) store and maps it to a URI. If the store already contains a mapping for the same URI, the existing mapping is overridden.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const ArrayPtr<uint8_t> &value, int32_t offset, int32_t count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | The URI of the data that is being added to the [XmlPreloadedResolver](../) store. |
| value | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A byte array with the data that corresponds to the provided URI. |
| offset | **int32_t** | The offset in the provided byte array where the data starts. |
| count | **int32_t** | The number of bytes to read from the byte array, starting at the provided offset. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const SharedPtr\<IO::Stream\>\&) method


Adds a Stream to the [XmlPreloadedResolver](../) store and maps it to a URI. If the store already contains a mapping for the same URI, the existing mapping is overridden.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const SharedPtr<IO::Stream> &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | The URI of the data that is being added to the [XmlPreloadedResolver](../) store. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | A Stream with the data that corresponds to the provided URI. |

## XmlPreloadedResolver::Add(const SharedPtr\<Uri\>\&, const String\&) method


Adds a string with preloaded data to the [XmlPreloadedResolver](../) store and maps it to a URI. If the store already contains a mapping for the same URI, the existing mapping is overridden.

```cpp
void System::Xml::Resolvers::XmlPreloadedResolver::Add(const SharedPtr<Uri> &uri, const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\& | The URI of the data that is being added to the [XmlPreloadedResolver](../) store. |
| value | const [String](../../../system/string/)\& | A [String](../../../system/string/) with the data that corresponds to the provided URI. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Uri](../../../system/uri/)
* Class [XmlPreloadedResolver](../)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)