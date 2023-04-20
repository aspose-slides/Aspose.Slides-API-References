---
title: Read()
second_title: Aspose.Slides for C++ API Reference
description: Reads the specified number of bytes from the stream and writes them to the specified byte array.
type: docs
weight: 391
url: /cpp/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Reads the specified number of bytes from the stream and writes them to the specified byte array.

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | The byte array to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### Return Value

The number of bytes read

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


Reads the specified number of bytes from the stream and writes them to the specified byte array.

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | The byte array to write the read bytes to |
| offset | **int32_t** | A 0-based position in **buffer** to start writing at |
| count | **int32_t** | The number of bytes to read |

### Return Value

The number of bytes read

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)