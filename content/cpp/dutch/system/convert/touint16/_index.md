---
title: ToUInt16()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven booleaanse waarde naar een gelijkwaardige 16-bit ongetekende integer.
type: docs
weight: 144
url: /nl/system/convert/touint16/
---
## Convert::ToUInt16(bool) methode


Converteert de opgegeven booleaanse waarde naar een gelijkwaardige 16-bit ongetekende integer.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(bool value)
```

## Convert::ToUInt16(uint8_t) methode


Converteert de opgegeven 8-bit ongetekende integer naar een gelijkwaardige 16-bit ongetekende integer.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(uint8_t value)
```

## Convert::ToUInt16(int8_t) methode


Converteert de opgegeven 8-bit ondertekende integer naar een gelijkwaardige 16-bit ongetekende integer.

```cpp
static uint16_t System::Convert::ToUInt16(int8_t value)
```

## Convert::ToUInt16(uint16_t) methode


Retourneert de opgegeven 16-bit ongetekende integer.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(uint16_t value)
```

## Convert::ToUInt16(int16_t) methode


Converteert de opgegeven 16-bit ondertekende integer naar een gelijkwaardige 16-bit ongetekende integer.

```cpp
static uint16_t System::Convert::ToUInt16(int16_t value)
```

## Convert::ToUInt16(uint32_t) methode


Converteert de opgegeven 32-bit ongetekende integer naar een gelijkwaardige 16-bit ongetekende integer.

```cpp
static uint16_t System::Convert::ToUInt16(uint32_t value)
```

## Convert::ToUInt16(int32_t) methode


Converteert de opgegeven 32-bit ondertekende integer naar een gelijkwaardige 16-bit ongetekende integer.

```cpp
static uint16_t System::Convert::ToUInt16(int32_t value)
```

## Convert::ToUInt16(uint64_t) methode


Converteert de opgegeven 64-bit ongetekende integer naar een gelijkwaardige 16-bit ongetekende integer.

```cpp
static uint16_t System::Convert::ToUInt16(uint64_t value)
```

## Convert::ToUInt16(int64_t) methode


Converteert de opgegeven 64-bit ondertekende integer naar een gelijkwaardige 16-bit ongetekende integer.

```cpp
static uint16_t System::Convert::ToUInt16(int64_t value)
```

## Convert::ToUInt16(float) methode


Converteert het opgegeven float-getal naar een gelijkwaardige 16-bit ongetekende integer.

```cpp
static uint16_t System::Convert::ToUInt16(float value)
```

## Convert::ToUInt16(double) methode


Converteert het opgegeven double-getal naar een gelijkwaardige 16-bit ongetekende integer.

```cpp
static uint16_t System::Convert::ToUInt16(double value)
```

## Convert::ToUInt16(const Decimal\&) methode


Converteert het opgegeven decimale getal naar een gelijkwaardige 16-bit ongetekende integer.

```cpp
static uint16_t System::Convert::ToUInt16(const Decimal &value)
```

## Convert::ToUInt16(char_t) methode


Converteert het opgegeven Unicode-teken naar een gelijkwaardige 16-bit ongetekende integer.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(char_t value)
```

## Convert::ToUInt16(DateTime) methode


Conversie wordt niet ondersteund. Gooit altijd een InvalidCastException.

```cpp
static uint16_t System::Convert::ToUInt16(DateTime value)
```

## Convert::ToUInt16(std::nullptr_t) methode


Converteert de opgegeven null-string naar de gelijkwaardige ongetekende 16-bit integerwaarde.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(std::nullptr_t)
```


### Retourwaarde

Nul.

## Convert::ToUInt16(const char_t *) methode


Converteert de opgegeven c-string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige ongetekende 16-bit integerwaarde.

```cpp
static uint16_t System::Convert::ToUInt16(const char_t *value)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | De c-string om te converteren |

### Retourwaarde

De ongetekende 16-bit integerwaarde gelijk aan het getal dat wordt weergegeven door de opgegeven c-string

## Convert::ToUInt16(const String\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige ongetekende 16-bit integerwaarde.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |

### Retourwaarde

De ongetekende 16-bit integerwaarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToUInt16(const String\&, int) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal in de opgegeven basis bevat naar de gelijkwaardige ongetekende 16-bit integerwaarde.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, int from_base)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |
| from_base | int | De basis van het getal dat door de string wordt weergegeven |

### Retourwaarde

De ongetekende 16-bit integerwaarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToUInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige ongetekende 16-bit integerwaarde met behulp van de meegeleverde opmaakinformatie.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaakinformatie bevat |

### Retourwaarde

De ongetekende 16-bit integerwaarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToUInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt16(const String\&, std::nullptr_t) methode




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, std::nullptr_t)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige ongetekende 16-bit integerwaarde met behulp van de meegeleverde opmaakinformatie en getalstijl.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise combinatie van waarden van de NumberStyles-enum die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaakinformatie bevat |

### Retourwaarde

De ongetekende 16-bit integerwaarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) methode




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt16(Enum) methode




```cpp
template<typename Enum,typename> static uint16_t System::Convert::ToUInt16(Enum value)
```

## Convert::ToUInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven geboxte waarde naar een gelijkwaardige ongetekende 16-bit integerwaarde.

```cpp
static uint16_t System::Convert::ToUInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | De gedeelde pointer naar het object dat de waarde boxt die moet worden geconverteerd |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | De tekenreeksopmaak die moet worden gebruikt als het type van de geboxte waarde [String](../../string/) is |

### Retourwaarde

Een ongetekende 16-bit integerwaarde gelijk aan de opgegeven geboxte waarde

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