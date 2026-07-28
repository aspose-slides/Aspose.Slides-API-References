---
title: GetFormat()
second_title: Aspose.Slides C++ számára API referencia
description: Lekéri a meghatározott típusú formázót.
type: docs
weight: 14
url: /hu/system.globalization/datetimeformatinfo/getformat/
---
## DateTimeFormatInfo::GetFormat(const TypeInfo\&) metódus

Megkapja a meghatározott típusú formatter-t.

```cpp
SharedPtr<Object> System::Globalization::DateTimeFormatInfo::GetFormat(const TypeInfo &format_type) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format_type | const [TypeInfo](../../../system/typeinfo/)\& | A lekérni kívánt formatter típusa; csak a [DateTimeFormatInfo](../) típus támogatott. |

### Visszatérési érték

Formatter vagy null, ha nem érhető el.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [TypeInfo](../../../system/typeinfo/)
* Osztály [DateTimeFormatInfo](../)
* Névtér [System::Globalization](../../)
* Könyvtár [Aspose.Slides](../../../)