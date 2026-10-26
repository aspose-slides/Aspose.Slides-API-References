---
title: ToChar()
second_title: Aspose.Slides voor C++ API-referentie
description: Conversie wordt niet ondersteund. Gooit altijd InvalidCastException.
type: docs
weight: 118
url: /nl/system/convert/tochar/
---
## Convert::ToChar(bool) methode

Conversie wordt niet ondersteund. Gooit altijd InvalidCastException.

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) methode

Converteert het opgegeven 8-bit unsigned integer naar een gelijkwaardig unicode-teken.

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) methode

Converteert het opgegeven 8-bit signed integer naar een gelijkwaardig unicode-teken.

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) methode

Converteert het opgegeven 16-bit unsigned integer naar een gelijkwaardig unicode-teken.

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) methode

Converteert het opgegeven 16-bit signed integer naar een gelijkwaardig unicode-teken.

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) methode

Converteert het opgegeven 32-bit unsigned integer naar een gelijkwaardig unicode-teken.

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) methode

Converteert het opgegeven 32-bit signed integer naar een gelijkwaardig unicode-teken.

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) methode

Converteert het opgegeven 64-bit unsigned integer naar een gelijkwaardig unicode-teken.

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) methode

Converteert het opgegeven 64-bit signed integer naar een gelijkwaardig unicode-teken.

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) methode

Conversie wordt niet ondersteund. Gooit altijd InvalidCastException.

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) methode

Conversie wordt niet ondersteund. Gooit altijd InvalidCastException.

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) methode

Conversie wordt niet ondersteund. Gooit altijd InvalidCastException.

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) methode

Retourneert het opgegeven unicode-teken.

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) methode

Conversie wordt niet ondersteund. Gooit altijd InvalidCastException.

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) methode

Converteert het eerste en enige teken van de opgegeven c-string naar een char_t-waarde.

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const char_t * | De c-string die moet worden geconverteerd; ervan wordt uitgegaan dat de c-string precies 1 teken lang is. |

### Retourwaarde

Het eerste en enige teken van de opgegeven c-string als deze exact 1 teken lang is, anders - 0

## Convert::ToChar(const String\&) methode

Converteert het eerste en enige teken van de opgegeven string naar een char_t-waarde.

```cpp
static char_t System::Convert::ToChar(const String &value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd; ervan wordt uitgegaan dat de string precies 1 teken lang is. |

### Retourwaarde

Het eerste en enige teken van de opgegeven string als deze exact 1 teken lang is, anders - 0

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) methode

Converteert het eerste en enige teken van de opgegeven string naar een char_t-waarde.

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd; ervan wordt uitgegaan dat de string precies 1 teken lang is. |

### Retourwaarde

Het eerste en enige teken van de opgegeven string als deze exact 1 teken lang is, anders - 0

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) methode

Converteert de opgegeven verpakte waarde naar een gelijkwaardig unicode-teken.

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | De gedeelde pointer naar het object dat de te converteren waarde verpakt. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Het string-formaat dat moet worden gebruikt als het type van de verpakte waarde [String](../../string/) is. |

### Retourwaarde

Een unicode-teken gelijkwaardig aan de opgegeven verpakte waarde

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)