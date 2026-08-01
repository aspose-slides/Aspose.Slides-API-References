---
title: ToUInt32()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven booleaanse waarde naar een gelijkwaardige 32-bit unsigned integer.
type: docs
weight: 170
url: /nl/system/convert/touint32/
---
## Convert::ToUInt32(bool) methode

Converteert de opgegeven booleaanse waarde naar een gelijkwaardige 32-bit unsigned integer.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(bool value)
```

## Convert::ToUInt32(uint8_t) methode

Converteert de opgegeven 8-bit unsigned integer naar een gelijkwaardige 32-bit unsigned integer.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint8_t value)
```

## Convert::ToUInt32(int8_t) methode

Converteert de opgegeven 8-bit signed integer naar een gelijkwaardige 32-bit unsigned integer.

```cpp
static uint32_t System::Convert::ToUInt32(int8_t value)
```

## Convert::ToUInt32(uint16_t) methode

Converteert de opgegeven 16-bit unsigned integer naar een gelijkwaardige 32-bit unsigned integer.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint16_t value)
```

## Convert::ToUInt32(int16_t) methode

Converteert de opgegeven 16-bit signed integer naar een gelijkwaardige 32-bit unsigned integer.

```cpp
static uint32_t System::Convert::ToUInt32(int16_t value)
```

## Convert::ToUInt32(uint32_t) methode

Returned the specified 32-bit unsigned integer.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint32_t value)
```

## Convert::ToUInt32(int32_t) methode

Converteert de opgegeven 32-bit signed integer naar een gelijkwaardige 32-bit unsigned integer.

```cpp
static uint32_t System::Convert::ToUInt32(int32_t value)
```

## Convert::ToUInt32(uint64_t) methode

Converteert de opgegeven 64-bit unsigned integer naar een gelijkwaardige 32-bit unsigned integer.

```cpp
static uint32_t System::Convert::ToUInt32(uint64_t value)
```

## Convert::ToUInt32(int64_t) methode

Converteert de opgegeven 64-bit signed integer naar een gelijkwaardige 32-bit unsigned integer.

```cpp
static uint32_t System::Convert::ToUInt32(int64_t value)
```

## Convert::ToUInt32(float) methode

Converteert het opgegeven float-getal naar een gelijkwaardige 32-bit unsigned integer.

```cpp
static uint32_t System::Convert::ToUInt32(float value)
```

## Convert::ToUInt32(double) methode

Converteert het opgegeven double-getal naar een gelijkwaardige 32-bit unsigned integer.

```cpp
static uint32_t System::Convert::ToUInt32(double value)
```

## Convert::ToUInt32(const Decimal\&) methode

Converteert het opgegeven decimal-getal naar een gelijkwaardige 32-bit unsigned integer.

```cpp
static uint32_t System::Convert::ToUInt32(const Decimal &value)
```

## Convert::ToUInt32(char_t) methode

Converteert het opgegeven unicode-teken naar een gelijkwaardige 32-bit unsigned integer.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(char_t value)
```

## Convert::ToUInt32(DateTime) methode

Conversie wordt niet ondersteund. Werpt altijd InvalidCastException.

```cpp
static uint32_t System::Convert::ToUInt32(DateTime value)
```

## Convert::ToUInt32(std::nullptr_t) methode

Converteert de opgegeven null-string naar de gelijkwaardige unsigned 32-bit integer-waarde.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(std::nullptr_t)
```


### Retourwaarde

Nul.

## Convert::ToUInt32(const char_t *) methode

Converteert de opgegeven c-string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige unsigned 32-bit integer-waarde.

```cpp
static uint32_t System::Convert::ToUInt32(const char_t *value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const char_t * | De c-string om te converteren |

### Retourwaarde

De unsigned 32-bit integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven c-string

## Convert::ToUInt32(const String\&) methode

Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige unsigned 32-bit integer-waarde.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren string |

### Retourwaarde

De unsigned 32-bit integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToUInt32(const String\&, int) methode

Converteert de opgegeven string die de tekenreeksrepresentatie van een getal in de opgegeven basis bevat naar de gelijkwaardige unsigned 32-bit integer-waarde.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, int from_base)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren string |
| from_base | int | De basis van het getal dat wordt weergegeven door de string |

### Retourwaarde

De unsigned 32-bit integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToUInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) methode

Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige unsigned 32-bit integer-waarde met behulp van de opgegeven opmaak-informatie.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren string |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeks-opmaak informatie bevat |

### Retourwaarde

De unsigned 32-bit integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, std::nullptr_t) methode




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, std::nullptr_t)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode

Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige unsigned 32-bit integer-waarde met behulp van de opgegeven opmaak-informatie en nummer-stijl.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren string |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise combinatie van waarden van de NumberStyles-enum die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeks-opmaak informatie bevat |

### Retourwaarde

De unsigned 32-bit integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) methode




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt32(Enum) methode




```cpp
template<typename Enum,typename> static uint32_t System::Convert::ToUInt32(Enum value)
```

## Convert::ToUInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) methode

Converteert de opgegeven verpakte waarde naar een gelijkwaardige unsigned 32-bit integer-waarde.

```cpp
static uint32_t System::Convert::ToUInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | De shared pointer naar het object dat de te converteren waarde verpakt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Het tekenreeksformaat dat moet worden gebruikt als het type van de verpakte waarde [String](../../string/) is |

### Retourwaarde

Een unsigned 32-bit integer-waarde gelijk aan de opgegeven verpakte waarde

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Decimal](../../decimal/)
* Klasse [DateTime](../../datetime/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Klasse [Object](../../object/)
* Struct [Convert](../)
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)