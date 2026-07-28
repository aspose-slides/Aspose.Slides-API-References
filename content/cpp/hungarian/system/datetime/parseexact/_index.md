---
title: ParseExact()
second_title: Aspose.Slides for C++ API referencia
description: Átalakítja a megadott dátum- és időértéket leíró karakterláncot a megfelelő DateTime objektummá a megadott formátum és kultúrafüggő formátuminformációk használatával. A karakterlánc formátumának pontosan meg kell egyeznie a megadott formátummal. Kivételt dob, ha az átalakítás sikertelen.
type: docs
weight: 872
url: /hu/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metódus


A megadott dátum- és időértéket leíró karakterlánc átalakítása a megfelelő [DateTime](../) objektummá a megadott formátum és kultúrafüggő formátuminformációk használatával. A karakterlánc formátumának pontosan meg kell egyeznie a megadott formátummal. Kivételt dob, ha az átalakítás sikertelen.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../string/)\& | A dátum- és időértéket leíró karakterlánc, amelyet konvertálni kell. |
| format | const [String](../../string/)\& | A karakterlánc formátuma. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A [IFormatProvider](../../iformatprovider/) objektum, amely kultúrafüggő formátuminformációkat biztosít. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Az enumerációs értékek bitenkénti kombinációja, amely további információkat szolgáltat a **s**-ről, a **s**-ben előforduló stíluselemekről, vagy a **s**-ből egy [DateTime](../) objektummá történő átalakításról. |

### Visszatérési érték

Egy új [DateTime](../) osztálypéldány, amely a megadott karakterlánc által ábrázolt dátum- és időértéknek megfelelően reprezentálja azt.

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metódus




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metódus




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) metódus




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metódus


A megadott dátum- és időértéket leíró karakterlánc átalakítása a megfelelő [DateTime](../) objektummá a megadott formátumok, a kultúrafüggő formátuminformációk és a stílus használatával. A karakterlánc formátumának pontosan meg kell egyeznie egy vagy több megadott formátummal. Kivételt dob, ha az átalakítás sikertelen.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../string/)\& | A dátum- és időértéket leíró karakterlánc, amelyet konvertálni kell. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | A karakterláncformátumok tömbje. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A [IFormatProvider](../../iformatprovider/) objektum, amely kultúrafüggő formátuminformációkat biztosít. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Az enumerációs értékek bitenkénti kombinációja, amely további információkat szolgáltat a **s**-ről, a **s**-ben előforduló stíluselemekről, vagy a **s**-ből egy [DateTime](../) objektummá történő átalakításról. |

### Visszatérési érték

Egy új [DateTime](../) osztálypéldány, amely a megadott karakterlánc által ábrázolt dátum- és időértéknek megfelelően reprezentálja azt.

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metódus




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metódus




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) metódus




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## See Also

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)