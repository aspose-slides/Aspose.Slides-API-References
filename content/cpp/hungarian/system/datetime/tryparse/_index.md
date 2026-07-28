---
title: TryParse()
second_title: Aspose.Slides for C++ API Referencia
description: Átalakítja a megadott dátum- és időérték karakterlánc ábrázolását az ekvivalens DateTime objektummá.
type: docs
weight: 885
url: /hu/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) metódus

Átalakítja a megadott dátum- és időérték karakterlánc ábrázolását a megfelelő [DateTime](../) objektummá.

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../string/)\& | A konvertálandó dátum- és időérték karakterlánc ábrázolása. |
| result | [DateTime](../)\& | A kimeneti argumentum, amely, ha a konvertálás sikeres, tartalmazza a konvertálás eredményét. |

### Visszatérési érték

true ha a konvertálás sikeres, egyébként - false.

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) metódus

Átalakítja a megadott dátum- és időérték karakterlánc ábrázolását a megfelelő [DateTime](../) objektummá a megadott kultúraspecifikus formátuminformációk és stílus felhasználásával.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| s | const [String](../../string/)\& | A konvertálandó dátum- és időérték karakterlánc ábrázolása. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A [IFormatProvider](../../iformatprovider/) objektum, amely kultúraspecifikus formátuminformációkat biztosít. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | A bitenkénti kombináció a felsorolt enumerációs értékekből, amely további információt nyújt a **s** karakterről, a **s**-ben előforduló stíluselemekről, vagy a **s**-ből egy [DateTime](../) objektummá történő konvertálásról. |
| result | [DateTime](../)\& | A kimeneti argumentum, amely, ha a konvertálás sikeres, tartalmazza a konvertálás eredményét. |

### Visszatérési érték

true ha a konvertálás sikeres, egyébként - false.

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metódus

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metódus

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) metódus

```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Lásd még

* enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* typedef [SharedPtr](../../sharedptr/)
* osztály [String](../../string/)
* osztály [DateTime](../)
* osztály [IFormatProvider](../../iformatprovider/)
* osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* osztály [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* névtér [System](../../)
* könyvtár [Aspose.Slides](../../../)