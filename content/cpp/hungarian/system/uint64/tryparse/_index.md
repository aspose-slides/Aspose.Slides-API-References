---
title: TryParse()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a megadott karakterláncot, amely egy szám karakterlánc ábrázolását tartalmazza, a megfelelő 64 bites előjel nélküli egész számmá.
type: docs
weight: 14
url: /hu/system/uint64/tryparse/
---
## UInt64::TryParse(const String&, uint64_t&) metódus


Átalakítja a szám karakterlánc ábrázolását tartalmazó megadott karakterláncot a megfelelő 64 bites előjel nélküli egész számmá.

```cpp
static bool System::UInt64::TryParse(const String &value, uint64_t &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)& | A konvertálandó karakterlánc. |
| result | **uint64_t**& | A 64 bites előjel nélküli egész változóra mutató referencia, amelybe a konverzió eredménye kerül. |

### Visszatérési érték

Igaz, ha a konverzió sikeres, egyébként – hamis.

## UInt64::TryParse(const String&, Globalization::NumberStyles, const SharedPtr<IFormatProvider>&, uint64_t&) metódus


Átalakítja a szám karakterlánc ábrázolását tartalmazó megadott karakterláncot a megfelelő 64 bites előjel nélküli egész számmá a megadott formázási információk és számstílus felhasználásával.

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint64_t &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)& | A konvertálandó karakterlánc. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles felsorolt típusának bitenkénti kombinációja, amely meghatározza a szám karakterlánc ábrázolásának megengedett stílusát. |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | Egy objektumra mutató pointer, amely tartalmazza a karakterlánc formátum információit. |
| result | **uint64_t**& | A 64 bites előjel nélküli egész változóra mutató referencia, amelybe a konverzió eredménye kerül. |

### Visszatérési érték

Igaz, ha a konverzió sikeres, egyébként – hamis.

## UInt64::TryParse(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::CultureInfo>&, uint64_t&) metódus




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint64_t &result)
```

## UInt64::TryParse(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::NumberFormatInfo>&, uint64_t&) metódus




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint64_t &result)
```

## UInt64::TryParse(const String&, Globalization::NumberStyles, std::nullptr_t, uint64_t&) metódus




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint64_t &result)
```

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* osztály [String](../../string/)
* osztály [IFormatProvider](../../iformatprovider/)
* osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* osztály [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt64](../)
* névtér [System](../../)
* Library [Aspose.Slides](../../../)