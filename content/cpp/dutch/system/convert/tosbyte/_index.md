---
title: ToSByte()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven boolean-waarde naar een gelijkwaardige 8-bit signed integer.
type: docs
weight: 105
url: /nl/system/convert/tosbyte/
---
## Convert::ToSByte(bool) methode


Converteert de opgegeven boolean-waarde naar een gelijkwaardige 8-bits signed integer.

```cpp
static constexpr int8_t System::Convert::ToSByte(bool value)
```

## Convert::ToSByte(uint8_t) methode


Converteert het opgegeven 8-bits unsigned geheel getal naar een gelijkwaardige 8-bits signed integer.

```cpp
static int8_t System::Convert::ToSByte(uint8_t value)
```

## Convert::ToSByte(int8_t) methode


Retourneert het opgegeven 8-bits signed geheel getal.

```cpp
static constexpr int8_t System::Convert::ToSByte(int8_t value)
```

## Convert::ToSByte(uint16_t) methode


Converteert het opgegeven 16-bits unsigned geheel getal naar een gelijkwaardige 8-bits signed integer.

```cpp
static int8_t System::Convert::ToSByte(uint16_t value)
```

## Convert::ToSByte(int16_t) methode


Converteert het opgegeven 16-bits signed geheel getal naar een gelijkwaardige 8-bits signed integer.

```cpp
static int8_t System::Convert::ToSByte(int16_t value)
```

## Convert::ToSByte(uint32_t) methode


Converteert het opgegeven 32-bits unsigned geheel getal naar een gelijkwaardige 8-bits signed integer.

```cpp
static int8_t System::Convert::ToSByte(uint32_t value)
```

## Convert::ToSByte(int32_t) methode


Converteert het opgegeven 32-bits signed geheel getal naar een gelijkwaardige 8-bits signed integer.

```cpp
static int8_t System::Convert::ToSByte(int32_t value)
```

## Convert::ToSByte(uint64_t) methode


Converteert het opgegeven 64-bits unsigned geheel getal naar een gelijkwaardige 8-bits signed integer.

```cpp
static int8_t System::Convert::ToSByte(uint64_t value)
```

## Convert::ToSByte(int64_t) methode


Converteert het opgegeven 64-bits signed geheel getal naar een gelijkwaardige 8-bits signed integer.

```cpp
static int8_t System::Convert::ToSByte(int64_t value)
```

## Convert::ToSByte(float) methode


Converteert het opgegeven float-getal naar een gelijkwaardige 8-bits signed integer.

```cpp
static int8_t System::Convert::ToSByte(float value)
```

## Convert::ToSByte(double) methode


Converteert het opgegeven double-getal naar een gelijkwaardige 8-bits signed integer.

```cpp
static int8_t System::Convert::ToSByte(double value)
```

## Convert::ToSByte(const Decimal\&) methode


Converteert het opgegeven decimal-getal naar een gelijkwaardige 8-bits signed integer.

```cpp
static int8_t System::Convert::ToSByte(const Decimal &value)
```

## Convert::ToSByte(char_t) methode


Converteert het opgegeven unicode-teken naar een gelijkwaardige 8-bits signed integer.

```cpp
static int8_t System::Convert::ToSByte(char_t value)
```

## Convert::ToSByte(DateTime) methode


Conversie wordt niet ondersteund. Gooit altijd InvalidCastException.

```cpp
static int8_t System::Convert::ToSByte(DateTime value)
```

## Convert::ToSByte(std::nullptr_t) methode


Converteert de opgegeven null-string naar de gelijkwaardige 8-bits integer-waarde.

```cpp
static constexpr int8_t System::Convert::ToSByte(std::nullptr_t)
```


### Retourwaarde

Nul.

## Convert::ToSByte(const char_t *) methode


Converteert de opgegeven c-string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige 8-bits integer-waarde.

```cpp
static int8_t System::Convert::ToSByte(const char_t *value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const char_t * | De c-string om te converteren |

### Retourwaarde

De 8-bits integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven c-string

## Convert::ToSByte(const String\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige 8-bits integer-waarde.

```cpp
static int8_t System::Convert::ToSByte(const String &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |

### Retourwaarde

De 8-bits integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToSByte(const String\&, int) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal in de opgegeven basis bevat naar de gelijkwaardige 8-bits integer-waarde.

```cpp
static int8_t System::Convert::ToSByte(const String &value, int from_base)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |
| from_base | int | De basis van het getal dat door de string wordt weergegeven |

### Retourwaarde

De 8-bits integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToSByte(const String\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige unsigned 8-bits integer-waarde met behulp van de opgegeven opmaak-informatie.

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de string-opmaak-informatie bevat |

### Retourwaarde

De 8-bits integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, std::nullptr_t) methode




```cpp
static int8_t System::Convert::ToSByte(const String &value, std::nullptr_t)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de gelijkwaardige 8-bits integer-waarde met behulp van de opgegeven opmaak-informatie en getalstijl.

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise-combinatie van waarden van de NumberStyles-enum die de toegestane stijl van de string-representatie van een getal specificeert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de string-opmaak-informatie bevat |

### Retourwaarde

De unsigned 8-bits integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, std::nullptr_t) methode 




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSByte(Enum) methode 




```cpp
template<typename Enum,typename> static int8_t System::Convert::ToSByte(Enum value)
```

## Convert::ToSByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven verpakte waarde naar een gelijkwaardige 8-bits integer-waarde.

```cpp
static int8_t System::Convert::ToSByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | De shared pointer naar het object dat de waarde verpakt die moet worden geconverteerd |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Het stringformaat dat moet worden gebruikt als het type van de verpakte waarde [String](../../string/) is |

### Retourwaarde

Een 8-bits integer-waarde gelijk aan de opgegeven verpakte waarde

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