---
title: ToInt64()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven booleaanse waarde naar een equivalent 64-bit ondertekend geheel getal.
type: docs
weight: 183
url: /nl/system/convert/toint64/
---
## Convert::ToInt64(bool) methode


Converteert de opgegeven booleaanse waarde naar een equivalent 64-bit ondertekend geheel getal.

```cpp
static constexpr int64_t System::Convert::ToInt64(bool value)
```

## Convert::ToInt64(uint8_t) methode


Converteert de opgegeven 8-bit niet-ondertekende geheel getal naar een equivalent 64-bit ondertekend geheel getal.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint8_t value)
```

## Convert::ToInt64(int8_t) methode


Converteert de opgegeven 8-bit ondertekende geheel getal naar een equivalent 64-bit ondertekend geheel getal.

```cpp
static constexpr int64_t System::Convert::ToInt64(int8_t value)
```

## Convert::ToInt64(uint16_t) methode


Converteert de opgegeven 16-bit niet-ondertekende geheel getal naar een equivalent 64-bit ondertekend geheel getal.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint16_t value)
```

## Convert::ToInt64(int16_t) methode


Converteert de opgegeven 16-bit ondertekende geheel getal naar een equivalent 64-bit ondertekend geheel getal.

```cpp
static constexpr int64_t System::Convert::ToInt64(int16_t value)
```

## Convert::ToInt64(uint32_t) methode


Converteert de opgegeven 32-bit niet-ondertekende geheel getal naar een equivalent 64-bit ondertekend geheel getal.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint32_t value)
```

## Convert::ToInt64(int32_t) methode


Converteert de opgegeven 32-bit ondertekende geheel getal naar een equivalent 64-bit ondertekend geheel getal.

```cpp
static constexpr int64_t System::Convert::ToInt64(int32_t value)
```

## Convert::ToInt64(uint64_t) methode


Converteert de opgegeven 64-bit niet-ondertekende geheel getal naar een equivalent 64-bit ondertekend geheel getal.

```cpp
static int64_t System::Convert::ToInt64(uint64_t value)
```

## Convert::ToInt64(int64_t) methode


Retourneert de opgegeven 64-bit ondertekende geheel getal.

```cpp
static constexpr int64_t System::Convert::ToInt64(int64_t value)
```

## Convert::ToInt64(float) methode


Converteert het opgegeven float-getal naar een equivalent 64-bit ondertekend geheel getal.

```cpp
static int64_t System::Convert::ToInt64(float value)
```

## Convert::ToInt64(double) methode


Converteert het opgegeven double-getal naar een equivalent 64-bit ondertekend geheel getal.

```cpp
static int64_t System::Convert::ToInt64(double value)
```

## Convert::ToInt64(const Decimal\&) methode


Converteert het opgegeven decimale getal naar een equivalent 64-bit ondertekend geheel getal.

```cpp
static int64_t System::Convert::ToInt64(const Decimal &value)
```

## Convert::ToInt64(char_t) methode


Converteert het opgegeven unicode-teken naar een equivalent 64-bit ondertekend geheel getal.

```cpp
static constexpr int64_t System::Convert::ToInt64(char_t value)
```

## Convert::ToInt64(DateTime) methode


Conversie wordt niet ondersteund. Werpt altijd InvalidCastException.

```cpp
static int64_t System::Convert::ToInt64(DateTime value)
```

## Convert::ToInt64(std::nullptr_t) methode


Converteert de opgegeven null-string naar de equivalente 64-bit integer-waarde.

```cpp
static constexpr int64_t System::Convert::ToInt64(std::nullptr_t)
```


### Returnwaarde

Zero.

## Convert::ToInt64(const char_t *) methode


Converteert de opgegeven c-string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 64-bit integer-waarde.

```cpp
static int64_t System::Convert::ToInt64(const char_t *value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const char_t * | De c-string om te converteren |

### Returnwaarde

De 64-bit integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven c-string

## Convert::ToInt64(const String\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 64-bit integer-waarde.

```cpp
static int64_t System::Convert::ToInt64(const String &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |

### Returnwaarde

De 64-bit integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToInt64(const String\&, int) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal in de opgegeven basis bevat naar de equivalente 64-bit integer-waarde.

```cpp
static int64_t System::Convert::ToInt64(const String &value, int from_base)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |
| from_base | int | De basis van het door de string gerepresenteerde getal |

### Returnwaarde

De 64-bit integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 64-bit integer-waarde met behulp van de opgegeven opmaakinformatie.

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaak-informatie bevat |

### Returnwaarde

De 64-bit integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, std::nullptr_t) methode




```cpp
static int64_t System::Convert::ToInt64(const String &value, std::nullptr_t)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 64-bit integer-waarde met behulp van de opgegeven opmaakinformatie en getalstijl.

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise-combinatie van waarden van de NumberStyles-enum die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaak-informatie bevat |

### Returnwaarde

De 64-bit integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) methode




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt64(Enum) methode




```cpp
template<typename Enum,typename> static int64_t System::Convert::ToInt64(Enum value)
```

## Convert::ToInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven verpakte waarde naar een equivalent 64-bit integer-waarde.

```cpp
static int64_t System::Convert::ToInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | De shared pointer naar het object dat de te converteren waarde verpakt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | De tekenreeksopmaak die wordt gebruikt als het type van de verpakte waarde [String](../../string/) is |

### Returnwaarde

Een 64-bit integer-waarde equivalent aan de opgegeven verpakte waarde

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