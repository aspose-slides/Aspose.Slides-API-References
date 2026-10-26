---
title: TryParseExact()
second_title: Aspose.Slides C++ API referencia
description: Megpróbálja a megadott karakterláncot a megadott formátumok, formátumszolgáltató és formázási stílus használatával DateTimeOffset objektummá konvertálni.
type: docs
weight: 742
url: /hu/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) módszer

Megpróbálja a megadott karakterláncot [DateTimeOffset](../) objektummá konvertálni a megadott formátumok, formátumszolgáltató és formázási stílus használatával.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) a konvertáláshoz. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Formátumkarakterláncok tömbjei. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátumszolgáltató. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Dátum- és időformázási stílusok. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) amely megegyezik a **input**-val. |

### Visszatérési érték

true, ha a **input** sikeresen konvertálódott, egyébként false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) módszer

Megpróbálja a megadott karakterláncot [DateTimeOffset](../) objektummá konvertálni a megadott formátum, formátumszolgáltató és formázási stílus használatával.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) a konvertáláshoz. |
| format | const [String](../../string/)\& | Formátumkarakterlánc. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formátumszolgáltató. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Dátum- és időformázási stílusok. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) amely megegyezik a **input**-val. |

### Visszatérési érték

true, ha a **input** sikeresen konvertálódott, egyébként false.

## Lásd még

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)