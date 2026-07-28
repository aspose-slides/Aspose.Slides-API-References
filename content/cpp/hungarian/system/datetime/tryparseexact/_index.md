---
title: TryParseExact()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a megadott dátum- és időérték karakterlánc ábrázolását a megfelelő DateTime objektummá a megadott formátum, kultúrára jellemző formátuminformációk és stílus használatával. A karakterlánc ábrázolásának formátumának pontosan meg kell egyeznie a megadott formátummal.
type: docs
weight: 898
url: /hu/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) metódus


Átalakítja a megadott dátum- és időérték karakterlánc ábrázolását a megfelelő [DateTime](../) objektummá a megadott formátum, kultúrára jellemző formátuminformációk és stílus használatával. A karakterlánc ábrázolásának formátumnak pontosan meg kell egyeznie a megadott formátummal.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | A dátum- és időérték karakterlánc ábrázolása, amelyet konvertálni kell. |
| format | const [String](../../string/)\& | A karakterlánc formátuma. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [IFormatProvider](../../iformatprovider/) objektum, amely kultúrára jellemző formátuminformációkat biztosít. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Az enumerációs értékek bitenkénti kombinációja, amely további információt ad **s**-ről, a **s**-ben előforduló stíluselemekről, vagy a **s**-től egy [DateTime](../) objektummá történő konverzióról. |
| result | [DateTime](../)\& | A kimeneti argumentum, amely ha a konverzió sikeres, tartalmazza a konverzió eredményét. |

### Visszatérési érték

True if conversion succeeds, otherwise - false.

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metódus




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metódus




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) metódus




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) metódus


Átalakítja a megadott dátum- és időérték karakterlánc ábrázolását a megfelelő [DateTime](../) objektummá a megadott formátumok, kultúrára jellemző formátuminformációk és stílus használatával. A karakterlánc ábrázolásának formátumának pontosan meg kell egyeznie egy vagy több megadott formátummal.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | A dátum- és időérték karakterlánc ábrázolása, amelyet konvertálni kell. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | A karakterlánc formátumok tömbje. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [IFormatProvider](../../iformatprovider/) objektum, amely kultúrára jellemző formátuminformációkat biztosít. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Az enumerációs értékek bitenkénti kombinációja, amely további információt ad **s**-ről, a **s**-ben előforduló stíluselemekről, vagy a **s**-től egy [DateTime](../) objektummá történő konverzióról. |
| result | [DateTime](../)\& | A kimeneti argumentum, amely ha a konverzió sikeres, tartalmazza a konverzió eredményét. |

### Visszatérési érték

True if conversion succeeds, otherwise - false.

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metódus




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metódus




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) metódus




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Lásd még

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTime](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)