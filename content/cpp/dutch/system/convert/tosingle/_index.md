---
title: ToSingle()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven booleaanse waarde naar een gelijkwaardig enkelprecisie zwevend-kommagetal.
type: docs
weight: 209
url: /nl/system/convert/tosingle/
---
## Convert::ToSingle(bool) methode

Converteert de opgegeven booleaanse waarde naar een gelijkwaardig enkelprecisie zwevend-kommagetal.

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```

## Convert::ToSingle(uint8_t) methode

Converteert de opgegeven 8-bit unsigned integer naar een gelijkwaardig enkelprecisie zwevend-kommagetal.

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```

## Convert::ToSingle(int8_t) methode

Converteert de opgegeven 8-bit signed integer naar een gelijkwaardig enkelprecisie zwevend-kommagetal.

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```

## Convert::ToSingle(uint16_t) methode

Converteert de opgegeven 16-bit unsigned integer naar een gelijkwaardig enkelprecisie zwevend-kommagetal.

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```

## Convert::ToSingle(int16_t) methode

Converteert de opgegeven 16-bit signed integer naar een gelijkwaardig enkelprecisie zwevend-kommagetal.

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```

## Convert::ToSingle(uint32_t) methode

Converteert de opgegeven 32-bit unsigned integer naar een gelijkwaardig enkelprecisie zwevend-kommagetal.

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```

## Convert::ToSingle(int32_t) methode

Converteert de opgegeven 32-bit signed integer naar een gelijkwaardig enkelprecisie zwevend-kommagetal.

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```

## Convert::ToSingle(uint64_t) methode

Converteert de opgegeven 64-bit unsigned integer naar een gelijkwaardig enkelprecisie zwevend-kommagetal.

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```

## Convert::ToSingle(int64_t) methode

Converteert de opgegeven 64-bit signed integer naar een gelijkwaardig enkelprecisie zwevend-kommagetal.

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```

## Convert::ToSingle(float) methode

Retourneert het opgegeven float-getal.

```cpp
static constexpr float System::Convert::ToSingle(float value)
```

## Convert::ToSingle(double) methode

Converteert het opgegeven double-precisie getal naar een gelijkwaardig enkelprecisie zwevend-kommagetal.

```cpp
static constexpr float System::Convert::ToSingle(double value)
```

## Convert::ToSingle(const Decimal\&) methode

Converteert het opgegeven decimale getal naar een gelijkwaardig enkelprecisie zwevend-kommagetal.

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```

## Convert::ToSingle(char_t) methode

Conversie wordt niet ondersteund. Werpt altijd InvalidCastException.

```cpp
static float System::Convert::ToSingle(char_t value)
```

## Convert::ToSingle(DateTime) methode

Conversie wordt niet ondersteund. Werpt altijd InvalidCastException.

```cpp
static float System::Convert::ToSingle(DateTime value)
```

## Convert::ToSingle(std::nullptr_t) methode

Converteert de opgegeven null-string naar het overeenkomstige enkelprecisie zwevend-kommagetal.

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```

### Retourwaarde

Nul.

## Convert::ToSingle(const char_t *) methode

Converteert de opgegeven c-string die de tekenreeksvoorstelling van een getal bevat naar het overeenkomstige enkelprecisie zwevend-kommagetal.

```cpp
static float System::Convert::ToSingle(const char_t *value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const char_t * | De te converteren c-string |

### Retourwaarde

Het enkelprecisie zwevend-kommagetal dat gelijk is aan het getal dat wordt weergegeven door de opgegeven c-string

## Convert::ToSingle(const String\&) methode

Converteert de opgegeven string die de tekenreeksvoorstelling van een getal bevat naar het overeenkomstige enkelprecisie zwevend-kommagetal.

```cpp
static float System::Convert::ToSingle(const String &value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren tekenreeks |

### Retourwaarde

Het enkelprecisie zwevend-kommagetal dat gelijk is aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToSingle(const String\&, const SharedPtr\<IFormatProvider\>\&) methode

Converteert de opgegeven string die de tekenreeksvoorstelling van een getal bevat naar het overeenkomstige enkelprecisie zwevend-kommagetal met behulp van de opgegeven opmaakinformatie.

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren tekenreeks |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeks-opmaakinformatie bevat |

### Retourwaarde

Het enkelprecisie zwevend-kommagetal dat gelijk is aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, std::nullptr_t) methode 




```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode

Converteert de opgegeven string die de tekenreeksvoorstelling van een getal bevat naar het overeenkomstige enkelprecisie zwevend-kommagetal met behulp van de opgegeven opmaakinformatie en getalstijl.

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren tekenreeks |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise-combinatie van waarden van de NumberStyles-enum die de toegestane stijl van de tekenreeksvoorstelling van een getal specificeert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeks-opmaakinformatie bevat |

### Retourwaarde

Het enkelprecisie zwevend-kommagetal dat gelijk is aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode 




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, std::nullptr_t) methode 




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) methode

Converteert de opgegeven verpakte waarde naar een enkelprecisie zwevend-kommagetal.

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | De shared pointer naar het object dat de te converteren waarde verpakt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | De tekenreeks-opmaak die moet worden gebruikt als het type van de verpakte waarde [String](../../string/) is |

### Retourwaarde

Een enkelprecisie zwevend-kommagetal dat gelijk is aan de opgegeven verpakte waarde

## Zie ook

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
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)