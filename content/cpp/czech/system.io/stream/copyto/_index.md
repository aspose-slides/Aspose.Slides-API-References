---
title: CopyTo()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Kopíruje bajty do určeného proudu.
type: docs
weight: 209
url: /cs/system.io/stream/copyto/
---
## Stream::CopyTo(const SharedPtr\<Stream\>\&) method


Kopíruje bajty do zadaného proudu.

```cpp
void System::IO::Stream::CopyTo(const SharedPtr<Stream> &destination)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| destination | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../)\>\& | [Stream](../) kam budou data zkopírována. |

## Stream::CopyTo(const SharedPtr\<Stream\>\&, int32_t) method


Kopíruje bajty do zadaného proudu pomocí určené velikosti vyrovnávací paměti.

```cpp
void System::IO::Stream::CopyTo(const SharedPtr<Stream> &destination, int32_t buffer_size)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| destination | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../)\>\& | [Stream](../) kam budou data zkopírována. |
| buffer_size | **int32_t** | Velikost vyrovnávací paměti. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Stream](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)