---
title: ToUInt64()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven booleaanse waarde naar een gelijkwaardige 64-bit unsigned integer.
type: docs
weight: 196
url: /nl/system/convert/touint64/
---
## Convert::ToUInt64(bool) methode

Converteert de opgegeven booleaanse waarde naar een gelijkwaardige 64-bit unsigned integer.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(bool value)
```

## Convert::ToUInt64(uint8_t) methode

Converteert de opgegeven 8-bit unsigned integer naar een gelijkwaardige 64-bit unsigned integer.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint8_t value)
```

## Convert::ToUInt64(int8_t) methode

Converteert de opgegeven 8-bit signed integer naar een gelijkwaardige 64-bit unsigned integer.

```cpp
static uint64_t System::Convert::ToUInt64(int8_t value)
```

## Convert::ToUInt64(uint16_t) methode

Converteert de opgegeven 16-bit unsigned integer naar een gelijkwaardige 64-bit unsigned integer.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint16_t value)
```

## Convert::ToUInt64(int16_t) methode

Converteert de opgegeven 16-bit signed integer naar een gelijkwaardige 64-bit unsigned integer.

```cpp
static uint64_t System::Convert::ToUInt64(int16_t value)
```

## Convert::ToUInt64(uint32_t) methode

Converteert de opgegeven 32-bit unsigned integer naar een gelijkwaardige 64-bit unsigned integer.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint32_t value)
```

## Convert::ToUInt64(int32_t) methode

Converteert de opgegeven 32-bit signed integer naar een gelijkwaardige 64-bit unsigned integer.

```cpp
static uint64_t System::Convert::ToUInt64(int32_t value)
```

## Convert::ToUInt64(uint64_t) methode

Retourneert de opgegeven 64-bit unsigned integer.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint64_t value)
```

## Convert::ToUInt64(int64_t) methode

Converteert de opgegeven 64-bit signed integer naar een gelijkwaardige 64-bit unsigned integer.

```cpp
static uint64_t System::Convert::ToUInt64(int64_t value)
```

## Convert::ToUInt64(float) methode

Converteert het opgegeven float-getal naar een gelijkwaardige 64-bit unsigned integer.

```cpp
static uint64_t System::Convert::ToUInt64(float value)
```

## Convert::ToUInt64(double) methode

Converteert het opgegeven double-getal naar een gelijkwaardige 64-bit unsigned integer.

```cpp
static uint64_t System::Convert::ToUInt64(double value)
```

## Convert::ToUInt64(const Decimal\&) methode

Converteert het opgegeven decimale getal naar een gelijkwaardige 64-bit unsigned integer.

```cpp
static uint64_t System::Convert::ToUInt64(const Decimal &value)
```

## Convert::ToUInt64(char_t) methode

Converteert het opgegeven Unicode-teken naar een gelijkwaardige 64-bit unsigned integer.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(char_t value)
```

## Convert::ToUInt64(DateTime) methode

Conversie wordt niet ondersteund. Gooit altijd InvalidCastException.

```cpp
static uint64_t System::Convert::ToUInt64(DateTime value)
```

## Convert::ToUInt64(std::nullptr_t) methode

Converteert de opgegeven null-string naar de overeenkomstige unsigned 64-bit integerwaarde.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(std::nullptr_t)
```


### Retourwaarde

Nul.

## Convert::ToUInt64(const char_t *) methode


Converteert de opgegeven c-string die de tekenreeksrepresentatie van een getal bevat naar de equivalente unsigned 64-bit integerwaarde.

```cpp
static uint64_t System::Convert::ToUInt64(const char_t *value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const char_t * | De c-string die moet worden geconverteerd |

### Retourwaarde

De unsigned 64-bit integerwaarde gelijk aan het getal dat wordt weergegeven door de opgegeven c-string

## Convert::ToUInt64(const String\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente unsigned 64-bit integerwaarde.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd |

### Retourwaarde

De unsigned 64-bit integerwaarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToUInt64(const String\&, int) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal in de opgegeven basis bevat naar de equivalente unsigned 64-bit integerwaarde.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, int from_base)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd |
| from_base | int | De basis van het getal dat wordt weergegeven door de string |

### Retourwaarde

De unsigned 64-bit integerwaarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToUInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente unsigned 64-bit integerwaarde met behulp van de opgegeven opmaakinformatie.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de stringopmaakinformatie bevat |

### Retourwaarde

De unsigned 64-bit integerwaarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, std::nullptr_t) methode




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, std::nullptr_t)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente unsigned 64-bit integerwaarde met behulp van de opgegeven opmaakinformatie en getalstijl.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise-combinatie van waarden van de NumberStyles-enum die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de stringopmaakinformatie bevat |

### Retourwaarde

De unsigned 64-bit integerwaarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) methode




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt64(Enum) methode




```cpp
template<typename Enum,typename> static uint64_t System::Convert::ToUInt64(Enum value)
```

## Convert::ToUInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven verpakte waarde naar een equivalente unsigned 64-bit integerwaarde.

```cpp
static uint64_t System::Convert::ToUInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | De gedeelde pointer naar het object dat de te converteren waarde verpakt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | De stringopmaak die moet worden gebruikt als het type van de verpakte waarde [String](../../string/) is |

### Retourwaarde

Een unsigned 64-bit integerwaarde gelijk aan de opgegeven verpakte waarde

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
* Naamruimte [System](../../)
* Library [Aspose.Slides](../../../)