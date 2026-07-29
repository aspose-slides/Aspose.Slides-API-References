---
title: Read()
second_title: Aspose.Slides för C++ API-referens
description: Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen.
type: docs
weight: 183
url: /sv/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod


Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen.

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Byte-arrayen att skriva de lästa byten till. |
| offset | **int32_t** | En 0-baserad position i **buffer** att börja skriva på. |
| count | **int32_t** | Antalet byte att läsa. |

### Return Value

Antalet lästa byte.

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod


Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen.

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Byte-array-vyn att skriva de lästa byten till. |
| offset | **int32_t** | En 0-baserad position i **buffer** att börja skriva på. |
| count | **int32_t** | Antalet byte att läsa. |

### Return Value

Antalet lästa byte.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [FileStream](../)
* Namnrymd [System::IO](../../)
* Library [Aspose.Slides](../../../)