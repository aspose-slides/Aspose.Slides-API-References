---
title: ParseExact()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a megadott karakterláncot DateTimeOffset objektummá a megadott formátum, formátumszolgáltató és formázási stílus használatával.
type: docs
weight: 716
url: /hu/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metódus

Átalakítja a megadott karakterláncot [DateTimeOffset](../) objektummá a megadott formátum, formátumszolgáltató és formázási stílus használatával.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) konvertáláshoz. |
| format | const [String](../../string/)\& | Formátum karakterlánc. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátumszolgáltató. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Dátum és idő formázási stílusok. |

### Visszatérési érték

[DateTimeOffset](../) amely megegyezik a **input** értékével.

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metódus

Átalakítja a megadott karakterláncot [DateTimeOffset](../) objektummá a megadott formátumok, formátumszolgáltató és formázási stílus használatával.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) konvertáláshoz. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) formátum karakterláncok. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátumszolgáltató. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Dátum és idő formázási stílusok. |

### Visszatérési érték

[DateTimeOffset](../) amely megegyezik a **input** értékével.

## Lásd még

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Osztály [DateTimeOffset](../)
* Osztály [String](../../string/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)