---
title: ToUInt32()
second_title: Aspose.Slides для C++ – справочник API
description: Преобразует четыре байта из указанного массива, начиная с указанного индекса, в беззнаковое 32-битное целое значение.
type: docs
weight: 105
url: /ru/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) method


Преобразует четыре байта из указанного массива, начиная с указанного индекса, в беззнаковое 32-битное целое значение.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) содержащий байты для преобразования |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### Return Value

Unsigned 32-bit integer value resulting from conversion

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) method


Преобразует четыре байта из указанного массива, начиная с указанного индекса, в беззнаковое 32-битное целое значение.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, содержащий байты для преобразования |
| startIndex | int | Index in the array at which to start taking bytes for conversion |

### Return Value

Unsigned 32-bit integer value resulting from conversion

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)