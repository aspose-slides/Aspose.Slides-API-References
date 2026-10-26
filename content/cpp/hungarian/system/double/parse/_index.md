---
title: Parse()
second_title: Aspose.Slides for C++ API Referencia
description: Átalakítja a megadott stringet, amely egy szám karakterábrázolását tartalmazza, az ekvivalens dupla pontosságú lebegőpontos értékké.
type: docs
weight: 1
url: /hu/system/double/parse/
---
## Double::Parse(const String\&) metódus


Átalakítja a megadott stringet, amely egy szám karakterábrázolását tartalmazza, az ekvivalens dupla pontosságú lebegőpontos értékké.

```cpp
static double System::Double::Parse(const String &value)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó string. |

### Visszatérési érték

Az a dupla pontosságú lebegőpontos érték, amely megegyezik a megadott string által ábrázolt számmal.

## Double::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott stringet, amely egy szám karakterábrázolását tartalmazza, az ekvivalens dupla pontosságú lebegőpontos értékké a megadott formázási információk felhasználásával.

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a stringformátum információit tartalmazza. |

### Visszatérési érték

Az a dupla pontosságú lebegőpontos érték, amely megegyezik a megadott string által ábrázolt számmal.

## Double::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, std::nullptr_t) metódus




```cpp
static double System::Double::Parse(const String &value, std::nullptr_t)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott stringet, amely egy szám karakterábrázolását tartalmazza, az ekvivalens dupla pontosságú lebegőpontos értékké a megadott formázási információk és számstílus felhasználásával.

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó string. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A NumberStyles enum értékeinek bitenkénti kombinációja, amely meghatározza a megengedett számjelölési stílust. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Egy mutató egy olyan objektumra, amely a stringformátum információit tartalmazza. |

### Visszatérési érték

Az a dupla pontosságú lebegőpontos érték, amely megegyezik a megadott string által ábrázolt számmal.

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metódus




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metódus 




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metódus 




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Lásd még

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [CultureInfo](../../../system.globalization/cultureinfo/)
* Osztály [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Névtér [System](../../)
* Library [Aspose.Slides](../../../)