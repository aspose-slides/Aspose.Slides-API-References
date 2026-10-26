---
title: ToDecimal()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven booleaanse waarde naar een gelijkwaardig decimaal getal.
type: docs
weight: 235
url: /nl/system/convert/todecimal/
---
## Convert::ToDecimal(bool) method


Converteert de opgegeven booleaanse waarde naar een gelijkwaardig decimaal getal.

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) method


Converteert de opgegeven 8-bit unsigned integer naar een gelijkwaardig decimaal getal.

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) method


Converteert de opgegeven 8-bit signed integer naar een gelijkwaardig decimaal getal.

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) method


Converteert de opgegeven 16-bit unsigned integer naar een gelijkwaardig decimaal getal.

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) method


Converteert de opgegeven 16-bit signed integer naar een gelijkwaardig decimaal getal.

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) method


Converteert de opgegeven 32-bit unsigned integer naar een gelijkwaardig decimaal getal.

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) method


Converteert de opgegeven 32-bit signed integer naar een gelijkwaardig decimaal getal.

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) method


Converteert de opgegeven 64-bit unsigned integer naar een gelijkwaardig decimaal getal.

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) method


Converteert de opgegeven 64-bit signed integer naar een gelijkwaardig decimaal getal.

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) method


Converteert het opgegeven float-getal naar een gelijkwaardig decimaal getal.

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) method


Converteert het opgegeven double-getal naar een gelijkwaardig decimaal getal.

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) method


Retourneert het opgegeven decimale getal.

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) method


Conversie wordt niet ondersteund. Gooit altijd InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) method


Conversie wordt niet ondersteund. Gooit altijd InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) method


Converteert de opgegeven null-string naar de equivalente [Decimal](../../decimal/)-waarde.

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```


### Retourwaarde

Nul.

## Convert::ToDecimal(const char_t *) method


Converteert de opgegeven c-string die de tekenreeksrepresentatie van een getal bevat naar de equivalente [Decimal](../../decimal/)-waarde.

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const char_t * | De c-string om te converteren |

### Retourwaarde

De [Decimal](../../decimal/)-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven c-string

## Convert::ToDecimal(const String\&) method


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente [Decimal](../../decimal/)-waarde.

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |

### Retourwaarde

De [Decimal](../../decimal/)-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) method


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente [Decimal](../../decimal/)-waarde met behulp van de opgegeven opmaakinformatie.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksformaatinformatie bevat |

### Retourwaarde

De [Decimal](../../decimal/)-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente [Decimal](../../decimal/)-waarde met behulp van de opgegeven nummers stijlen en opmaakinformatie.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bit-gewijze combinatie van waarden van de NumberStyles-enum die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksformaatinformatie bevat |

### Retourwaarde

De [Decimal](../../decimal/)-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method


Converteert de opgegeven verpakte waarde naar een equivalente [Decimal](../../decimal/)-waarde.

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | De gedeelde pointer naar het object dat de te converteren waarde verpakt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Het tekenreeksformaat dat moet worden gebruikt als het type van de verpakte waarde [String](../../string/) is |

### Retourwaarde

Een [Decimal](../../decimal/)-waarde gelijk aan de opgegeven verpakte waarde

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Decimal](../../decimal/)
* Klasse [DateTime](../../datetime/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)