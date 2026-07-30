---
title: ToString()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací řetězcovou reprezentaci hodnoty data a času reprezentované aktuálním objektem pomocí formátovacích konvencí definovaných aktuální kulturou.
type: docs
weight: 482
url: /cs/system/datetime/tostring/
---
## DateTime::ToString() const metoda


Vrací řetězcovou reprezentaci hodnoty data a času reprezentované aktuálním objektem pomocí formátovacích konvencí definovaných aktuální kulturou.

```cpp
String System::DateTime::ToString() const
```


### Návratová hodnota

Řetězcová reprezentace hodnoty reprezentované aktuálním objektem

## DateTime::ToString(const String\&) const metoda


Vrací řetězcovou reprezentaci hodnoty data a času reprezentované aktuálním objektem pomocí zadaného formátu a formátovacích konvencí definovaných aktuální kulturou.

```cpp
String System::DateTime::ToString(const String &format) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| format | const [String](../../string/)\& | Formátovací řetězec |

### Návratová hodnota

Řetězcová reprezentace hodnoty reprezentované aktuálním objektem formátovaná podle formátu definovaného **format** a aktuální kultury.

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const metoda


Vrací řetězcovou reprezentaci hodnoty data a času reprezentované aktuálním objektem pomocí specifikovaných informací o formátu.

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objekt představující informace o formátu |

### Návratová hodnota

Řetězcová reprezentace hodnoty reprezentované aktuálním objektem formátovaná podle informací o formátu poskytnutých **formatProvider**.

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const metoda




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const metoda




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const metoda




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const metoda


Vrací řetězcovou reprezentaci hodnoty data a času reprezentované aktuálním objektem pomocí specifikovaných informací o formátu.

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| format | const [String](../../string/)\& | Formátovací řetězec |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objekt představující informace o formátu |

### Návratová hodnota

Řetězcová reprezentace hodnoty reprezentované aktuálním objektem formátovaná podle informací o formátu poskytnutých **provider** a řetězce formátu **format**.

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metoda




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const metoda




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const metoda




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## Viz také

* Definice typu [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Třída [DateTime](../)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)