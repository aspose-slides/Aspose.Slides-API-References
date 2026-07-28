---
title: TryParse()
second_title: Aspose.Slides a C++ API referencia
description: Megpróbálja a megadott karakterláncot DateTimeOffset objektummá konvertálni.
type: docs
weight: 729
url: /hu/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) metódus

Megpróbálja a megadott karakterláncot [DateTimeOffset](../) objektummá konvertálni.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) a konvertáláshoz. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../), amely megegyezik a **input**-al. |

### Visszatérési érték

true, ha a **input** sikeresen konvertálódott, egyébként - false.

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) metódus

Megpróbálja a megadott karakterláncot [DateTimeOffset](../) objektummá konvertálni a megadott formátumszolgáltató és formázási stílus használatával.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) a konvertáláshoz. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátum szolgáltató. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Dátum és idő formázási stílusok. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../), amely megegyezik a **input**-al. |

### Visszatérési érték

true, ha a **input** sikeresen konvertálódott, egyébként - false.

## Lásd még

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)