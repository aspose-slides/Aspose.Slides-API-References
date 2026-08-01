---
title: ToDouble()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven booleaanse waarde naar een gelijkwaardige double-precision floating-point-waarde.
type: docs
weight: 222
url: /nl/system/convert/todouble/
---
## Convert::ToDouble(bool) methode


Converteert de opgegeven booleaanse waarde naar een gelijkwaardige double-precision floating-point-waarde.

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```

## Convert::ToDouble(uint8_t) methode


Converteert de opgegeven 8-bit unsigned integer naar een gelijkwaardige double-precision floating-point-waarde.

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```

## Convert::ToDouble(int8_t) methode


Converteert de opgegeven 8-bit signed integer naar een gelijkwaardige double-precision floating-point-waarde.

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```

## Convert::ToDouble(uint16_t) methode


Converteert de opgegeven 16-bit unsigned integer naar een gelijkwaardige double-precision floating-point-waarde.

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```

## Convert::ToDouble(int16_t) methode


Converteert de opgegeven 16-bit signed integer naar een gelijkwaardige double-precision floating-point-waarde.

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```

## Convert::ToDouble(uint32_t) methode


Converteert de opgegeven 32-bit unsigned integer naar een gelijkwaardige double-precision floating-point-waarde.

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```

## Convert::ToDouble(int32_t) methode


Converteert de opgegeven 32-bit signed integer naar een gelijkwaardige double-precision floating-point-waarde.

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```

## Convert::ToDouble(uint64_t) methode


Converteert de opgegeven 64-bit unsigned integer naar een gelijkwaardige double-precision floating-point-waarde.

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```

## Convert::ToDouble(int64_t) methode


Converteert de opgegeven 64-bit signed integer naar een gelijkwaardige double-precision floating-point-waarde.

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```

## Convert::ToDouble(float) methode


Converteert het opgegeven single-precision getal naar een gelijkwaardige double-precision floating-point-waarde.

```cpp
static constexpr double System::Convert::ToDouble(float value)
```

## Convert::ToDouble(double) methode


Retourneert het opgegeven double-getal.

```cpp
static constexpr double System::Convert::ToDouble(double value)
```

## Convert::ToDouble(const Decimal\&) methode


Converteert het opgegeven decimale getal naar een gelijkwaardige double-precision floating-point-waarde.

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```

## Convert::ToDouble(char_t) methode


Conversie wordt niet ondersteund. Werpt altijd InvalidCastException.

```cpp
static double System::Convert::ToDouble(char_t value)
```

## Convert::ToDouble(DateTime) methode


Conversie wordt niet ondersteund. Werpt altijd InvalidCastException.

```cpp
static double System::Convert::ToDouble(DateTime value)
```

## Convert::ToDouble(std::nullptr_t) methode


Converteert de opgegeven null-string naar de equivalente double-precision floating-point-waarde.

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```


### Retourwaarde

Nul.

## Convert::ToDouble(const char_t *) methode


Converteert de opgegeven c-string die de tekenreeksrepresentatie van een getal bevat naar de equivalente double-precision floating-point-waarde.

```cpp
static double System::Convert::ToDouble(const char_t *value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const char_t * | De c-string om te converteren |

### Retourwaarde

De double-precision floating-point-waarde die gelijk is aan het getal dat wordt weergegeven door de opgegeven c-string

## Convert::ToDouble(const String\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente double-precision floating-point-waarde.

```cpp
static double System::Convert::ToDouble(const String &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |

### Retourwaarde

De double-precision floating-point-waarde die gelijk is aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente double-precision floating-point-waarde met behulp van de opgegeven opmaakinformatie.

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de string-indelingsinformatie bevat |

### Retourwaarde

De double-precision floating-point-waarde die gelijk is aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) methode




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente double-precision floating-point-waarde met behulp van de opgegeven opmaakinformatie en getalstijl.

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise-combinatie van waarden uit de NumberStyles-enum die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de string-indelingsinformatie bevat |

### Retourwaarde

De double-precision floating-point-waarde die gelijk is aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) methode




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven ingepakte waarde naar een double-precision floating-point-waarde. Als het type van de ingepakte waarde [String](../../string/) is, wordt tijdens de conversie het opgegeven string-formaat gebruikt.

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | De shared pointer naar het object dat de te converteren waarde verpakt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Het string-formaat dat moet worden gebruikt als het type van de ingepakte waarde [String](../../string/) is |

### Retourwaarde

Een double-precision floating-point-waarde die gelijk is aan de opgegeven ingepakte waarde

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