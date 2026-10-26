---
title: ToDouble()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Převádí osm bajtů ze zadaného pole počínaje zadaným indexem na hodnotu s dvojitou přesností floating point.
type: docs
weight: 144
url: /cs/system/bitconverter/todouble/
---
## BitConverter::ToDouble(const System::ArrayPtr\<uint8_t\>\&, int) method

Převádí osm bajtů ze zadaného pole počínaje zadaným indexem na hodnotu s dvojitou přesností floating point.

```cpp
static double System::BitConverter::ToDouble(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) který obsahuje bajty k převodu |
| startIndex | int | [Index](../../index/) v poli, od kterého začít odebírat bajty pro převod |

### Return Value

Hodnota s dvojitou přesností floating-point získaná převodem

## BitConverter::ToDouble(const System::Details::ArrayView\<uint8_t\>\&, int) method

Převádí osm bajtů ze zadaného pole počínaje zadaným indexem na hodnotu s dvojitou přesností floating point.

```cpp
static double System::BitConverter::ToDouble(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView který obsahuje bajty k převodu |
| startIndex | int | [Index](../../index/) v poli, od kterého začít odebírat bajty pro převod |

### Return Value

Hodnota s dvojitou přesností floating-point získaná převodem

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Třída [BitConverter](../)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)