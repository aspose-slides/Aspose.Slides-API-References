---
title: ToByte()
second_title: Aspose.Slides C++ API-referencia
description: Átalakítja a megadott logikai értéket egy megfelelő 8 bites előjel nélküli egész számmá.
type: docs
weight: 92
url: /hu/system/convert/tobyte/
---
## Convert::ToByte(bool) metódus

Átalakítja a megadott logikai értéket egy megfelelő 8 bites előjel nélküli egész számmá.

```cpp
static constexpr uint8_t System::Convert::ToByte(bool value)
```
## Convert::ToByte(uint8_t) metódus

Visszaadja a megadott 8 bites előjel nélküli egész számot.

```cpp
static constexpr uint8_t System::Convert::ToByte(uint8_t value)
```
## Convert::ToByte(int8_t) metódus

Átalakítja a megadott 8 bites előjeles egész számot egy megfelelő 8 bites előjel nélküli egész számmá.

```cpp
static uint8_t System::Convert::ToByte(int8_t value)
```
## Convert::ToByte(uint16_t) metódus

Átalakítja a megadott 16 bites előjel nélküli egész számot egy megfelelő 8 bites előjel nélküli egész számmá.

```cpp
static uint8_t System::Convert::ToByte(uint16_t value)
```
## Convert::ToByte(int16_t) metódus

Átalakítja a megadott 16 bites előjeles egész számot egy megfelelő 8 bites előjel nélküli egész számmá.

```cpp
static uint8_t System::Convert::ToByte(int16_t value)
```
## Convert::ToByte(uint32_t) metódus

Átalakítja a megadott 32 bites előjel nélküli egész számot egy megfelelő 8 bites előjel nélküli egész számmá.

```cpp
static uint8_t System::Convert::ToByte(uint32_t value)
```
## Convert::ToByte(int32_t) metódus

Átalakítja a megadott 32 bites előjeles egész számot egy megfelelő 8 bites előjel nélküli egész számmá.

```cpp
static uint8_t System::Convert::ToByte(int32_t value)
```
## Convert::ToByte(uint64_t) metódus

Átalakítja a megadott 64 bites előjel nélküli egész számot egy megfelelő 8 bites előjel nélküli egész számmá.

```cpp
static uint8_t System::Convert::ToByte(uint64_t value)
```
## Convert::ToByte(int64_t) metódus

Átalakítja a megadott 64 bites előjeles egész számot egy megfelelő 8 bites előjel nélküli egész számmá.

```cpp
static uint8_t System::Convert::ToByte(int64_t value)
```
## Convert::ToByte(float) metódus

Átalakítja a megadott lebegőpontos számot egy megfelelő 8 bites előjel nélküli egész számmá.

```cpp
static uint8_t System::Convert::ToByte(float value)
```
## Convert::ToByte(double) metódus

Átalakítja a megadott dupla pontosságú számot egy megfelelő 8 bites előjel nélküli egész számmá.

```cpp
static uint8_t System::Convert::ToByte(double value)
```
## Convert::ToByte(const Decimal\&) metódus

Átalakítja a megadott decimális számot egy megfelelő 8 bites előjel nélküli egész számmá.

```cpp
static uint8_t System::Convert::ToByte(const Decimal &value)
```
## Convert::ToByte(char_t) metódus

Átalakítja a megadott Unicode karaktert egy megfelelő 8 bites előjel nélküli egész számmá.

```cpp
static uint8_t System::Convert::ToByte(char_t value)
```
## Convert::ToByte(DateTime) metódus

Az átalakítás nincs támogatva. Mindig InvalidCastException kivételt dob.

```cpp
static uint8_t System::Convert::ToByte(DateTime value)
```
## Convert::ToByte(std::nullptr_t) metódus

Átalakítja a megadott null-karakterláncot a megfelelő előjel nélküli 8 bites egész értékké.

```cpp
static constexpr uint8_t System::Convert::ToByte(std::nullptr_t)
```

### Visszatérési érték

Nulla.

## Convert::ToByte(const char_t *) metódus

Átalakítja a megadott c-stringet, amely egy szám szöveges ábrázolását tartalmazza, a megfelelő előjel nélküli 8 bites egész értékké.

```cpp
static uint8_t System::Convert::ToByte(const char_t *value)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | Az átalakítandó c-string |

### Visszatérési érték

Az előjel nélküli 8 bites egész érték, amely megegyezik a megadott c-string által ábrázolt számmal.

## Convert::ToByte(const String\&) metódus

Átalakítja a megadott stringet, amely egy szám szöveges ábrázolását tartalmazza, a megfelelő előjel nélküli 8 bites egész értékké.

```cpp
static uint8_t System::Convert::ToByte(const String &value)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó string |

### Visszatérési érték

Az előjel nélküli 8 bites egész érték, amely megegyezik a megadott string által ábrázolt számmal.

## Convert::ToByte(const String\&, int) metódus

Átalakítja a megadott stringet, amely a megadott alapban egy szám szöveges ábrázolását tartalmazza, a megfelelő előjel nélküli 8 bites egész értékké.

```cpp
static uint8_t System::Convert::ToByte(const String &value, int from_base)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó string |
| from_base | int | A szám alapja, amelyet a string ábrázol |

### Visszatérési érték

Az előjel nélküli 8 bites egész érték, amely megegyezik a megadott string által ábrázolt számmal.

## Convert::ToByte(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus

Átalakítja a megadott stringet, amely egy szám szöveges ábrázolását tartalmazza, a megfelelő előjel nélküli 8 bites egész értékké a megadott formázási információk felhasználásával.

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó string |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a string formátuminformációkat tartalmazza |

### Visszatérési érték

Az előjel nélküli 8 bites egész érték, amely megegyezik a megadott string által ábrázolt számmal.

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metódus

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, std::nullptr_t) method

```cpp
static uint8_t System::Convert::ToByte(const String &value, std::nullptr_t)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metódus

Átalakítja a megadott stringet, amely egy szám szöveges ábrázolását tartalmazza, a megfelelő előjel nélküli 8 bites egész értékké a megadott formázási információk és számalap használatával.

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó string |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles enum értékeinek bitenkénti kombinációja, amely meghatározza a szám szöveges ábrázolásának megengedett stílusát |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a string formátuminformációkat tartalmazza |

### Visszatérési érték

Az előjel nélküli 8 bites egész érték, amely megegyezik a megadott string által ábrázolt számmal.

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metódus

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, std::nullptr_t) method

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToByte(Enum) method

```cpp
template<typename Enum,typename> static uint8_t System::Convert::ToByte(Enum value)
```

## Convert::ToByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metódus

Átalakítja a megadott dobozott értéket egy megfelelő előjel nélküli 8 bites egész értékké.

```cpp
static uint8_t System::Convert::ToByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Az objektum megosztott mutatója, amely a konvertálandó értéket becsomagolja |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A string formátum, amelyet akkor használunk, ha a becsomagolt érték típusa [String](../../string/) |

### Visszatérési érték

Egy előjel nélküli 8 bites egész érték, amely megegyezik a megadott becsomagolt értékkel.

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)