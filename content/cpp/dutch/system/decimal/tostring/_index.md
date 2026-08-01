---
title: ToString()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de tekenreeksrepresentatie van de waarde die door het object wordt weergegeven.
type: docs
weight: 352
url: /nl/system/decimal/tostring/
---
## Decimal::ToString() const methode


Retourneert de tekenreeksrepresentatie van de waarde die door het object wordt vertegenwoordigd.

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const methode


Converteert het huidige object naar een tekenreeks met behulp van de cultuurspecifieke opmaakinformatie.

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Het [IFormatProvider](../../iformatprovider/)-object dat de cultuurspecifieke opmaakinformatie levert. |

### Returnwaarde

De tekenreeksrepresentatie van het huidige object.

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const methode




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const methode




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const methode




```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const methode


Converteert het huidige object naar zijn tekenreeksrepresentatie met behulp van het opgegeven tekenreeksformaat en de cultuurspecifieke opmaakinformatie die wordt geleverd door het opgegeven [IFormatProvider](../../iformatprovider/)-object.

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../../string/)\& | Het tekenreeksformaat. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Het [IFormatProvider](../../iformatprovider/)-object dat de cultuurspecifieke opmaakinformatie levert. |

### Returnwaarde

De tekenreeksrepresentatie van het huidige object.

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const methode 




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const methode 




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const methode 




```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Decimal](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)