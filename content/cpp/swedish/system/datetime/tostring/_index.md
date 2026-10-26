---
title: ToString()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar strängrepresentationen av datum- och tidsvärdet som representeras av det aktuella objektet med de formatkonventionerna som definieras av den aktuella kulturen.
type: docs
weight: 482
url: /sv/system/datetime/tostring/
---
## DateTime::ToString() const metod


Returnerar strängrepresentationen av datum- och tidsvärdet som representeras av det aktuella objektet med formatkonventionerna som definieras av den aktuella kulturen.

```cpp
String System::DateTime::ToString() const
```


### Returvärde

Strängrepresentationen av värdet som representeras av det aktuella objektet

## DateTime::ToString(const String\&) const metod


Returnerar en strängrepresentation av datum- och tidsvärdet som representeras av det aktuella objektet med det angivna formatet och formatkonventionerna som definieras av den aktuella kulturen.

```cpp
String System::DateTime::ToString(const String &format) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | const [String](../../string/)\& | En formatsträng |

### Returvärde

Strängrepresentationen av värdet som representeras av det aktuella objektet formaterad enligt formatet som definieras av **format** och den aktuella kulturen.

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const metod


Returnerar en strängrepresentation av datum- och tidsvärdet som representeras av det aktuella objektet med den angivna formatinformationen.

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ett objekt som representerar formatinformationen |

### Returvärde

Strängrepresentationen av värdet som representeras av det aktuella objektet formaterad enligt formatinformation som tillhandahålls av **formatProvider**.

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const metod




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const metod




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const metod




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const metod


Returnerar en strängrepresentation av datum- och tidsvärdet som representeras av det aktuella objektet med den angivna formatinformationen.

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | const [String](../../string/)\& | En formatsträng |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ett objekt som representerar formatinformationen |

### Returvärde

Strängrepresentationen av värdet som representeras av det aktuella objektet formaterad enligt formatinformation som tillhandahålls av **provider** och formatsträngen **format**.

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metod




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const metod




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const metod




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [DateTime](../)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)