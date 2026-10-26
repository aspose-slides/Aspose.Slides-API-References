---
title: FromBase64CharArray()
second_title: Aspose.Slides für C++ API-Referenz
description: Dekodiert Base-64-codierte Daten, die als Bereich im Array von Unicode-Zeichen dargestellt werden.
type: docs
weight: 53
url: /de/system/convert/frombase64chararray/
---
## Convert::FromBase64CharArray(const ArrayPtr\<char_t\>\&, int, int) Methode

Dekodiert base-64-codierte Daten, die als Bereich im Array von Unicode-Zeichen dargestellt werden.

```cpp
static ArrayPtr<uint8_t> System::Convert::FromBase64CharArray(const ArrayPtr<char_t> &in_array, int offset, int length)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Das Array, das die zu dekodierenden Daten enthält |
| offset | int | Die Position im Eingabearray, an der der zu dekodierende Bereich beginnt |
| length | int | Die Länge des zu dekodierenden Bereichs |

### Rückgabewert

Ein Byte-Array, das die dekodierten Daten enthält

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)