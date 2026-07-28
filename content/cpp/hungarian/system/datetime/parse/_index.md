---
title: Parse()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a megadott dátum- és időérték karakterlánc ábrázolását az ekvivalens DateTime objektummá.
type: docs
weight: 859
url: /hu/system/datetime/parse/
---
## DateTime::Parse(const String\&) metódus


Átalakítja a megadott dátum- és időértéket reprezentáló karakterláncot a megfelelő [DateTime](../) objektummá.

```cpp
static DateTime System::DateTime::Parse(const String &s)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../string/)\& | A konvertálandó dátum- és időérték karakterlánc ábrázolása. |

### Visszatérési érték

Az új [DateTime](../) osztálypéldány, amely a megadott karakterlánc által reprezentált dátum- és időértéket képviseli.

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metódus


Átalakítja a megadott dátum- és időértéket reprezentáló karakterláncot a megfelelő [DateTime](../) objektummá kultúraspecifikus formátuminformációk felhasználásával.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../string/)\& | A konvertálandó dátum- és időérték karakterlánc ábrázolása. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A [IFormatProvider](../../iformatprovider/) objektum, amely kultúraspecifikus formátuminformációkat biztosít. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | A bitenkénti kombinációja az enumeráció értékeinek, amely további információkat biztosít **s**, az **s**-ben előforduló stíluselemekről, vagy a **s** [DateTime](../) objektummá történő átalakításáról. |

### Visszatérési érték

Az új [DateTime](../) osztálypéldány, amely a megadott karakterlánc által reprezentált dátum- és időértéket képviseli.

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metódus




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metódus




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) metódus




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Lásd még

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Osztály [DateTime](../)
* Osztály [String](../../string/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)