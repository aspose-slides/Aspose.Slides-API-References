---
title: FromBase64CharArray()
second_title: Aspose.Slides för C++ API-referens
description: Avkodar base-64-kodad data som representeras som ett intervall i arrayen av Unicode-tecken.
type: docs
weight: 53
url: /sv/system/convert/frombase64chararray/
---
## Convert::FromBase64CharArray(const ArrayPtr\<char_t\>\&, int, int) metod

Avkodar base-64-kodad data som representeras som ett intervall i arrayen av Unicode-tecken.

```cpp
static ArrayPtr<uint8_t> System::Convert::FromBase64CharArray(const ArrayPtr<char_t> &in_array, int offset, int length)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Arrayen som innehåller data att avkoda |
| offset | int | Positionen i inmatningsarrayen där intervallet att avkoda börjar |
| length | int | Längden på intervallet att avkoda |

### Returvärde

En byte-array som innehåller den avkodade datan

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namnrymd [System](../../)
* Library [Aspose.Slides](../../../)