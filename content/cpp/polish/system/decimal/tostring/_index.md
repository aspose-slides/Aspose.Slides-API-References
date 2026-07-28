---
title: ToString()
second_title: Aspose.Slides dla referencji API C++
description: Zwraca tekstową reprezentację wartości reprezentowanej przez obiekt.
type: docs
weight: 352
url: /pl/system/decimal/tostring/
---
## Decimal::ToString() const metoda


Zwraca tekstową reprezentację wartości reprezentowanej przez obiekt.

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const metoda


Konwertuje bieżący obiekt na ciąg znaków przy użyciu informacji o formacie specyficznym dla kultury.

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Obiekt [IFormatProvider](../../iformatprovider/) dostarczający informacje o formacie specyficznym dla kultury. |

### Wartość zwracana

Tekstowa reprezentacja bieżącego obiektu.

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const metoda




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const metoda




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const metoda




```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const metoda


Konwertuje bieżący obiekt na jego reprezentację znakową przy użyciu określonego formatu ciągu znaków i informacji o formacie specyficznym dla kultury, dostarczonych przez określony obiekt [IFormatProvider](../../iformatprovider/).

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| format | const [String](../../string/)\& | Format ciągu znaków. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Obiekt [IFormatProvider](../../iformatprovider/) dostarczający informacje o formacie specyficznym dla kultury. |

### Wartość zwracana

Tekstowa reprezentacja bieżącego obiektu.

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metoda




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const metoda




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const metoda




```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## Zobacz także

* Typedef [SharedPtr](../../sharedptr/)
* Klasa [String](../../string/)
* Klasa [Decimal](../)
* Klasa [IFormatProvider](../../iformatprovider/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)