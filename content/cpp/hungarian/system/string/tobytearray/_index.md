---
title: ToByteArray()
second_title: Aspose.Slides C++ API referenciája
description: Átalakítja a stringet vagy részstringet bájt tömbbé.
type: docs
weight: 508
url: /hu/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const metódus

Átalakítja a string vagy részstringet bájt tömbbé.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```

### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | **int32_t** | A részstring kezdőindexe. |
| length | **int32_t** | A részstring hossza. |
| LE | **bool** | Ha true, a karaktereket kisvégű bájt formátumban kódolja; egyébként nagyvégű bájt formátumban. |

### Return Value

[Array](../../array/) tartalmazza a string karaktereit reprezentáló bájtokat.

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [String](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)