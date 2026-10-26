---
title: ToByte()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven booleaanse waarde naar een gelijkwaardige 8-bit unsigned integer.
type: docs
weight: 92
url: /nl/system/convert/tobyte/
---
## Convert::ToByte(bool) methode

Converteert de opgegeven booleaanse waarde naar een gelijkwaardige 8-bit unsigned integer.

```cpp
static constexpr uint8_t System::Convert::ToByte(bool value)
```
## Convert::ToByte(uint8_t) methode

Retourneert de opgegeven 8-bit unsigned integer.

```cpp
static constexpr uint8_t System::Convert::ToByte(uint8_t value)
```
## Convert::ToByte(int8_t) methode

Converteert de opgegeven 8-bit signed integer naar een gelijkwaardige 8-bit unsigned integer.

```cpp
static uint8_t System::Convert::ToByte(int8_t value)
```
## Convert::ToByte(uint16_t) methode

Converteert de opgegeven 16-bit unsigned integer naar een gelijkwaardige 8-bit unsigned integer.

```cpp
static uint8_t System::Convert::ToByte(uint16_t value)
```
## Convert::ToByte(int16_t) methode

Converteert de opgegeven 16-bit signed integer naar een gelijkwaardige 8-bit unsigned integer.

```cpp
static uint8_t System::Convert::ToByte(int16_t value)
```
## Convert::ToByte(uint32_t) methode

Converteert de opgegeven 32-bit unsigned integer naar een gelijkwaardige 8-bit unsigned integer.

```cpp
static uint8_t System::Convert::ToByte(uint32_t value)
```
## Convert::ToByte(int32_t) methode

Converteert de opgegeven 32-bit signed integer naar een gelijkwaardige 8-bit unsigned integer.

```cpp
static uint8_t System::Convert::ToByte(int32_t value)
```
## Convert::ToByte(uint64_t) methode

Converteert de opgegeven 64-bit unsigned integer naar een gelijkwaardige 8-bit unsigned integer.

```cpp
static uint8_t System::Convert::ToByte(uint64_t value)
```
## Convert::ToByte(int64_t) methode

Converteert de opgegeven 64-bit signed integer naar een gelijkwaardige 8-bit unsigned integer.

```cpp
static uint8_t System::Convert::ToByte(int64_t value)
```
## Convert::ToByte(float) methode

Converteert het opgegeven float-getal naar een gelijkwaardige 8-bit unsigned integer.

```cpp
static uint8_t System::Convert::ToByte(float value)
```
## Convert::ToByte(double) methode

Converteert het opgegeven double-getal naar een gelijkwaardige 8-bit unsigned integer.

```cpp
static uint8_t System::Convert::ToByte(double value)
```
## Convert::ToByte(const Decimal\&) methode

Converteert het opgegeven decimal-getal naar een gelijkwaardige 8-bit unsigned integer.

```cpp
static uint8_t System::Convert::ToByte(const Decimal &value)
```
## Convert::ToByte(char_t) methode

Converteert het opgegeven Unicode-teken naar een gelijkwaardige 8-bit unsigned integer.

```cpp
static uint8_t System::Convert::ToByte(char_t value)
```
## Convert::ToByte(DateTime) methode

Conversie wordt niet ondersteund. Werpt altijd InvalidCastException.

```cpp
static uint8_t System::Convert::ToByte(DateTime value)
```
## Convert::ToByte(std::nullptr_t) methode

Converteert de opgegeven null-string naar de gelijkwaardige unsigned 8-bit integer-waarde.

```cpp
static constexpr uint8_t System::Convert::ToByte(std::nullptr_t)
```


### Retourwaarde

Nul.

## Convert::ToByte(const char_t *) methode


Converteert de opgegeven c-string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige unsigned 8-bit integer-waarde.

```cpp
static uint8_t System::Convert::ToByte(const char_t *value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const char_t * | De c-string die moet worden geconverteerd |

### Retourwaarde

De unsigned 8-bit integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven c-string

## Convert::ToByte(const String\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige unsigned 8-bit integer-waarde.

```cpp
static uint8_t System::Convert::ToByte(const String &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd |

### Retourwaarde

De unsigned 8-bit integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToByte(const String\&, int) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal in de opgegeven basis bevat naar de gelijkwaardige unsigned 8-bit integer-waarde.

```cpp
static uint8_t System::Convert::ToByte(const String &value, int from_base)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd |
| from_base | int | De basis van het getal dat door de string wordt weergegeven |

### Retourwaarde

De unsigned 8-bit integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToByte(const String\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige unsigned 8-bit integer-waarde met behulp van de opgegeven opmaakinformatie.

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaakinformatie bevat |

### Retourwaarde

De unsigned 8-bit integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, std::nullptr_t) methode




```cpp
static uint8_t System::Convert::ToByte(const String &value, std::nullptr_t)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige unsigned 8-bit integer-waarde met behulp van de opgegeven opmaakinformatie en nummerstijl.

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise-combinatie van waarden van de NumberStyles-enum die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaakinformatie bevat |

### Retourwaarde

De unsigned 8-bit integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, std::nullptr_t) methode




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToByte(Enum) methode




```cpp
template<typename Enum,typename> static uint8_t System::Convert::ToByte(Enum value)
```

## Convert::ToByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven verpakte waarde naar een gelijkwaardige unsigned 8-bit integer-waarde.

```cpp
static uint8_t System::Convert::ToByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | De shared pointer naar het object dat de te converteren waarde verpakt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | De tekenreeksopmaak die moet worden gebruikt als het type van de verpakte waarde [String](../../string/) is |

### Retourwaarde

Een unsigned 8-bit integer-waarde gelijk aan de opgegeven verpakte waarde

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
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)