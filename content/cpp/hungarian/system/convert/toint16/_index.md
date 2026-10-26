---
title: ToInt16()
second_title: Aspose.Slides C++ API referencia
description: Átalakítja a megadott logikai értéket egy ekvivalens 16 bites előjeles egész számmá.
type: docs
weight: 131
url: /hu/system/convert/toint16/
---
## Convert::ToInt16(bool) metódus

Átalakítja a megadott logikai értéket egy ekvivalens 16 bites előjeles egész számmá.

```cpp
static constexpr int16_t System::Convert::ToInt16(bool value)
```
## Convert::ToInt16(uint8_t) metódus

Átalakítja a megadott 8 bites előjel nélküli egész számot egy ekvivalens 16 bites előjeles egész számmá.

```cpp
static constexpr int16_t System::Convert::ToInt16(uint8_t value)
```
## Convert::ToInt16(int8_t) metódus

Átalakítja a megadott 8 bites előjeles egész számot egy ekvivalens 16 bites előjeles egész számmá.

```cpp
static constexpr int16_t System::Convert::ToInt16(int8_t value)
```
## Convert::ToInt16(uint16_t) metódus

Átalakítja a megadott 16 bites előjel nélküli egész számot egy ekvivalens 16 bites előjeles egész számmá.

```cpp
static int16_t System::Convert::ToInt16(uint16_t value)
```
## Convert::ToInt16(int16_t) metódus

Visszaadja a megadott 16 bites előjeles egész számot.

```cpp
static constexpr int16_t System::Convert::ToInt16(int16_t value)
```
## Convert::ToInt16(uint32_t) metódus

Átalakítja a megadott 32 bites előjel nélküli egész számot egy ekvivalens 16 bites előjeles egész számmá.

```cpp
static int16_t System::Convert::ToInt16(uint32_t value)
```
## Convert::ToInt16(int32_t) metódus

Átalakítja a megadott 32 bites előjeles egész számot egy ekvivalens 16 bites előjeles egész számmá.

```cpp
static int16_t System::Convert::ToInt16(int32_t value)
```
## Convert::ToInt16(uint64_t) metódus

Átalakítja a megadott 64 bites előjel nélküli egész számot egy ekvivalens 16 bites előjeles egész számmá.

```cpp
static int16_t System::Convert::ToInt16(uint64_t value)
```
## Convert::ToInt16(int64_t) metódus

Átalakítja a megadott 64 bites előjeles egész számot egy ekvivalens 16 bites előjeles egész számmá.

```cpp
static int16_t System::Convert::ToInt16(int64_t value)
```
## Convert::ToInt16(float) metódus

Átalakítja a megadott lebegőpontos számot egy ekvivalens 16 bites előjeles egész számmá.

```cpp
static int16_t System::Convert::ToInt16(float value)
```
## Convert::ToInt16(double) metódus

Átalakítja a megadott dupla pontosságú számot egy ekvivalens 16 bites előjeles egész számmá.

```cpp
static int16_t System::Convert::ToInt16(double value)
```
## Convert::ToInt16(const Decimal\&) metódus

Átalakítja a megadott decimális számot egy ekvivalens 16 bites előjeles egész számmá.

```cpp
static int16_t System::Convert::ToInt16(const Decimal &value)
```
## Convert::ToInt16(char_t) metódus

Átalakítja a megadott Unicode karaktert egy ekvivalens 16 bites előjeles egész számmá.

```cpp
static int16_t System::Convert::ToInt16(char_t value)
```
## Convert::ToInt16(DateTime) metódus

Az átalakítás nem támogatott. Mindig InvalidCastException kivételt dob.

```cpp
static int16_t System::Convert::ToInt16(DateTime value)
```
## Convert::ToInt16(std::nullptr_t) metódus

Átalakítja a megadott null-karakterláncot az ekvivalens 16 bites egész számmá.

```cpp
static constexpr int16_t System::Convert::ToInt16(std::nullptr_t)
```


### Return Value

Nulla.

## Convert::ToInt16(const char_t *) metódus


Átalakítja a megadott c-karakterláncot, amely számként ábrázolja a számot, az ekvivalens 16 bites egész értékké.

```cpp
static int16_t System::Convert::ToInt16(const char_t *value)
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const char_t * | A konvertálandó c-karakterlánc |

### Return Value

A 16-bites egész érték, amely megegyezik a megadott c-karakterláncban ábrázolt számmal.

## Convert::ToInt16(const String\&) metódus


Átalakítja a megadott sztringet, amely számként ábrázolja a számot, az ekvivalens 16 bites egész értékké.

```cpp
static int16_t System::Convert::ToInt16(const String &value)
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó sztring |

### Return Value

A 16-bites egész érték, amely megegyezik a megadott sztringben ábrázolt számmal.

## Convert::ToInt16(const String\&, int) metódus


Átalakítja a megadott sztringet, amely a megadott számrendszerben ábrázolja a számot, az ekvivalens 16 bites egész értékké.

```cpp
static int16_t System::Convert::ToInt16(const String &value, int from_base)
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó sztring |
| from_base | int | A sztringben ábrázolt szám alapja |

### Return Value

A 16-bites egész érték, amely megegyezik a megadott sztringben ábrázolt számmal

## Convert::ToInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott sztringet, amely számot ábrázol, az ekvivalens 16 bites egész értékké a megadott formázási információk felhasználásával.

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó sztring |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató az objektumra, amely a sztring formátuminformációt tartalmazza |

### Return Value

A 16-bites egész érték, amely megegyezik a megadott sztringben ábrázolt számmal

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, std::nullptr_t) metódus




```cpp
static int16_t System::Convert::ToInt16(const String &value, std::nullptr_t)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott sztringet, amely számot ábrázol, az ekvivalens 16 bites egész értékké a megadott formázási információk és számstílus felhasználásával.

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó sztring |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles felsorolt értékek bitenkénti kombinációja, amely meghatározza az engedélyezett sztringformátumot |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató az objektumra, amely a sztring formátuminformációt tartalmazza |

### Return Value

A 16-bites egész érték, amely megegyezik a megadott sztringben ábrázolt számmal

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) metódus




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt16(Enum) metódus




```cpp
template<typename Enum,typename> static int16_t System::Convert::ToInt16(Enum value)
```

## Convert::ToInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott becsomagolt értéket egy ekvivalens 16 bites egész értékké.

```cpp
static int16_t System::Convert::ToInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | A megosztott mutató az objektumra, amely a konvertálandó értéket becsomagolja |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A sztringformátum, amelyet akkor használunk, ha a becsomagolt érték típusa [String](../../string/) |

### Return Value

Egy 16-bites egész érték, amely ekvivalens a megadott becsomagolt értékkel

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Osztály [Decimal](../../decimal/)
* Osztály [DateTime](../../datetime/)
* Osztály [String](../../string/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Osztály [Object](../../object/)
* Struktúra [Convert](../)
* Struktúra [Enum](../../enum/)
* Névtér [System](../../)
* Library [Aspose.Slides](../../../)