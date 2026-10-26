---
title: GetFormat()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Formatter eines bestimmten Typs zurück.
type: docs
weight: 14
url: /de/system.globalization/datetimeformatinfo/getformat/
---
## DateTimeFormatInfo::GetFormat(const TypeInfo\&) Methode

Gibt den Formatter des angegebenen Typs zurück.

```cpp
SharedPtr<Object> System::Globalization::DateTimeFormatInfo::GetFormat(const TypeInfo &format_type) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format_type | const [TypeInfo](../../../system/typeinfo/)\& | Typ des zu erhaltenden Formatters; nur [DateTimeFormatInfo](../) Typ wird unterstützt. |

### Rückgabewert

Formatter oder null, wenn nicht verfügbar.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [DateTimeFormatInfo](../)
* Namensraum [System::Globalization](../../)
* Bibliothek [Aspose.Slides](../../../)