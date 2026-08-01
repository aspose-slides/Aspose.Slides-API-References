---
title: ToInt16()
second_title: Aspose.Slides voor C++ API Referentie
description: Converteert de opgegeven booleaanse waarde naar een equivalente 16-bit ondertekende integer.
type: docs
weight: 131
url: /nl/system/convert/toint16/
---
## Convert::ToInt16(bool) methode

Converteert de opgegeven booleaanse waarde naar een equivalente 16-bit ondertekende integer.

```cpp
static constexpr int16_t System::Convert::ToInt16(bool value)
```

## Convert::ToInt16(uint8_t) methode

Converteert de opgegeven 8-bit unsigned integer naar een equivalente 16-bit ondertekende integer.

```cpp
static constexpr int16_t System::Convert::ToInt16(uint8_t value)
```

## Convert::ToInt16(int8_t) methode

Converteert de opgegeven 8-bit signed integer naar een equivalente 16-bit ondertekende integer.

```cpp
static constexpr int16_t System::Convert::ToInt16(int8_t value)
```

## Convert::ToInt16(uint16_t) methode

Converteert de opgegeven 16-bit unsigned integer naar een equivalente 16-bit ondertekende integer.

```cpp
static int16_t System::Convert::ToInt16(uint16_t value)
```

## Convert::ToInt16(int16_t) methode

Geeft de opgegeven 16-bit signed integer terug.

```cpp
static constexpr int16_t System::Convert::ToInt16(int16_t value)
```

## Convert::ToInt16(uint32_t) methode

Converteert de opgegeven 32-bit unsigned integer naar een equivalente 16-bit ondertekende integer.

```cpp
static int16_t System::Convert::ToInt16(uint32_t value)
```

## Convert::ToInt16(int32_t) methode

Converteert de opgegeven 32-bit signed integer naar een equivalente 16-bit ondertekende integer.

```cpp
static int16_t System::Convert::ToInt16(int32_t value)
```

## Convert::ToInt16(uint64_t) methode

Converteert de opgegeven 64-bit unsigned integer naar een equivalente 16-bit ondertekende integer.

```cpp
static int16_t System::Convert::ToInt16(uint64_t value)
```

## Convert::ToInt16(int64_t) methode

Converteert de opgegeven 64-bit signed integer naar een equivalente 16-bit ondertekende integer.

```cpp
static int16_t System::Convert::ToInt16(int64_t value)
```

## Convert::ToInt16(float) methode

Converteert het opgegeven float-nummer naar een equivalente 16-bit ondertekende integer.

```cpp
static int16_t System::Convert::ToInt16(float value)
```

## Convert::ToInt16(double) methode

Converteert het opgegeven double-nummer naar een equivalente 16-bit ondertekende integer.

```cpp
static int16_t System::Convert::ToInt16(double value)
```

## Convert::ToInt16(const Decimal\&) methode

Converteert het opgegeven decimale getal naar een equivalente 16-bit ondertekende integer.

```cpp
static int16_t System::Convert::ToInt16(const Decimal &value)
```

## Convert::ToInt16(char_t) methode

Converteert het opgegeven Unicode-teken naar een equivalente 16-bit ondertekende integer.

```cpp
static int16_t System::Convert::ToInt16(char_t value)
```

## Convert::ToInt16(DateTime) methode

Conversie wordt niet ondersteund. Werpt altijd InvalidCastException.

```cpp
static int16_t System::Convert::ToInt16(DateTime value)
```

## Convert::ToInt16(std::nullptr_t) methode

Converteert de opgegeven null-string naar de equivalente 16-bit integerwaarde.

```cpp
static constexpr int16_t System::Convert::ToInt16(std::nullptr_t)
```


### Retourwaarde

Nul.

## Convert::ToInt16(const char_t *) methode

Converteert de opgegeven c-string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 16-bit integerwaarde.

```cpp
static int16_t System::Convert::ToInt16(const char_t *value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const char_t * | De c-string om te converteren |

### Retourwaarde

De 16-bit integerwaarde gelijk aan het getal dat door de opgegeven c-string wordt weergegeven

## Convert::ToInt16(const String\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 16-bit integerwaarde.

```cpp
static int16_t System::Convert::ToInt16(const String &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |

### Retourwaarde

De 16-bit integerwaarde gelijk aan het getal dat door de opgegeven string wordt weergegeven

## Convert::ToInt16(const String\&, int) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal in de opgegeven basis bevat naar de equivalente 16-bit integerwaarde.

```cpp
static int16_t System::Convert::ToInt16(const String &value, int from_base)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |
| from_base | int | De basis van het getal dat door de string wordt weergegeven |

### Retourwaarde

De 16-bit integerwaarde gelijk aan het getal dat door de opgegeven string wordt weergegeven

## Convert::ToInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 16-bit integerwaarde met behulp van de opgegeven opmaakinformatie.

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de stringformaatinformatie bevat |

### Retourwaarde

De 16-bit integerwaarde gelijk aan het getal dat door de opgegeven string wordt weergegeven

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, std::nullptr_t) methode




```cpp
static int16_t System::Convert::ToInt16(const String &value, std::nullptr_t)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 16-bit integerwaarde met behulp van de opgegeven opmaakinformatie en getalstijl.

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise-combinatie van waarden van de NumberStyles-enum die de toegestane stijl van de stringrepresentatie van een getal specificeert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de stringformaatinformatie bevat |

### Retourwaarde

De 16-bit integerwaarde gelijk aan het getal dat door de opgegeven string wordt weergegeven

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) methode




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt16(Enum) methode




```cpp
template<typename Enum,typename> static int16_t System::Convert::ToInt16(Enum value)
```

## Convert::ToInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven ingepakte waarde naar een equivalente 16-bit integerwaarde.

```cpp
static int16_t System::Convert::ToInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | De shared pointer naar het Object die de te converteren waarde inpakt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Het string-formaat dat moet worden gebruikt als het type van de ingepakte waarde [String](../../string/) is |

### Retourwaarde

Een 16-bit integerwaarde gelijk aan de opgegeven ingepakte waarde

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