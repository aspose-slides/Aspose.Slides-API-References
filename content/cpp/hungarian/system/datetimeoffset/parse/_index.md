---
title: Parse()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a megadott karakterláncot a DateTimeOffset megfelelőre.
type: docs
weight: 703
url: /hu/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) metódus


Átalakítja a megadott karakterláncot [DateTimeOffset](../) megfelelőre.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) átalakítandó. |

### Visszatérési érték

[DateTimeOffset](../) amely megegyezik a **input**-mal.

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metódus


Átalakítja a megadott karakterláncot [DateTimeOffset](../) objektummá a megadott formázó szolgáltató és formázási stílus használatával.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) átalakítandó. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formázó szolgáltató. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Dátum- és időformázási stílusok. |

### Visszatérési érték

[DateTimeOffset](../) amely megegyezik a **input**-mal.

## Lásd még

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Osztály [DateTimeOffset](../)
* Osztály [String](../../string/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Névtér [System](../../)
* Library [Aspose.Slides](../../../)