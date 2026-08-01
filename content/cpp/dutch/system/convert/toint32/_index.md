---
title: ToInt32()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven booleanwaarde naar een equivalent 32-bit ondertekend geheel getal.
type: docs
weight: 157
url: /nl/system/convert/toint32/
---
## Convert::ToInt32(bool) methode

Converteert de opgegeven booleanwaarde naar een equivalent 32-bits ondertekend geheel getal.

```cpp
static constexpr int System::Convert::ToInt32(bool value)
```

## Convert::ToInt32(uint8_t) methode

Converteert de opgegeven 8-bits unsigned integer naar een equivalent 32-bits ondertekend geheel getal.

```cpp
static constexpr int System::Convert::ToInt32(uint8_t value)
```

## Convert::ToInt32(int8_t) methode

Converteert de opgegeven 8-bits signed integer naar een equivalent 32-bits ondertekend geheel getal.

```cpp
static constexpr int System::Convert::ToInt32(int8_t value)
```

## Convert::ToInt32(uint16_t) methode

Converteert de opgegeven 16-bits unsigned integer naar een equivalent 32-bits ondertekend geheel getal.

```cpp
static constexpr int System::Convert::ToInt32(uint16_t value)
```

## Convert::ToInt32(int16_t) methode

Converteert de opgegeven 16-bits signed integer naar een equivalent 32-bits ondertekend geheel getal.

```cpp
static constexpr int System::Convert::ToInt32(int16_t value)
```

## Convert::ToInt32(uint32_t) methode

Converteert de opgegeven 32-bits unsigned integer naar een equivalent 32-bits ondertekend geheel getal.

```cpp
static int System::Convert::ToInt32(uint32_t value)
```

## Convert::ToInt32(int32_t) methode

Retourneert de opgegeven 32-bits signed integer.

```cpp
static constexpr int System::Convert::ToInt32(int32_t value)
```

## Convert::ToInt32(uint64_t) methode

Converteert de opgegeven 64-bits unsigned integer naar een equivalent 32-bits ondertekend geheel getal.

```cpp
static int System::Convert::ToInt32(uint64_t value)
```

## Convert::ToInt32(int64_t) methode

Converteert de opgegeven 64-bits signed integer naar een equivalent 32-bits ondertekend geheel getal.

```cpp
static int System::Convert::ToInt32(int64_t value)
```

## Convert::ToInt32(float) methode

Converteert het opgegeven float-getal naar een equivalent 32-bits ondertekend geheel getal.

```cpp
static int System::Convert::ToInt32(float value)
```

## Convert::ToInt32(double) methode

Converteert het opgegeven double-getal naar een equivalent 32-bits ondertekend geheel getal.

```cpp
static int System::Convert::ToInt32(double value)
```

## Convert::ToInt32(const Decimal\&) methode

Converteert het opgegeven decimal-getal naar een equivalent 32-bits ondertekend geheel getal.

```cpp
static int System::Convert::ToInt32(const Decimal &value)
```

## Convert::ToInt32(char_t) methode

Converteert het opgegeven unicode-teken naar een equivalent 32-bits ondertekend geheel getal.

```cpp
static constexpr int System::Convert::ToInt32(char_t value)
```

## Convert::ToInt32(DateTime) methode

Conversie wordt niet ondersteund. Werpt altijd InvalidCastException.

```cpp
static int System::Convert::ToInt32(DateTime value)
```

## Convert::ToInt32(std::nullptr_t) methode

Converteert de opgegeven null-string naar de equivalente 32-bits integer-waarde.

```cpp
static constexpr int System::Convert::ToInt32(std::nullptr_t)
```

### Retourwaarde

Zero.

## Convert::ToInt32(const char_t *) methode

Converteert de opgegeven c-string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 32-bits integer-waarde.

```cpp
static int System::Convert::ToInt32(const char_t *value)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | De c-string die moet worden geconverteerd |

### Retourwaarde

De 32-bits integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven c-string

## Convert::ToInt32(const String\&) methode

Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 32-bits integer-waarde.

```cpp
static int System::Convert::ToInt32(const String &value)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd |

### Retourwaarde

De 32-bits integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToInt32(const String\&, int) methode

Converteert de opgegeven string die de tekenreeksrepresentatie van een getal in de opgegeven basis bevat naar de equivalente 32-bits integer-waarde.

```cpp
static int System::Convert::ToInt32(const String &value, int from_base)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd |
| from_base | int | De grondtal van het getal dat door de string wordt weergegeven |

### Retourwaarde

De 32-bits integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) methode

Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 32-bits integer-waarde met behulp van de meegeleverde opmaak-informatie.

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeks-opmaak-informatie bevat |

### Retourwaarde

De 32-bits integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, std::nullptr_t) methode




```cpp
static int System::Convert::ToInt32(const String &value, std::nullptr_t)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) methode

Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente 32-bits integer-waarde met behulp van de meegeleverde opmaak-informatie en getalstijl.

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string die moet worden geconverteerd |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise-combinatie van waarden van de enum NumberStyles die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeks-opmaak-informatie bevat |

### Retourwaarde

De 32-bits integer-waarde gelijk aan het getal dat wordt weergegeven door de opgegeven string

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) methode




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) methode




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) methode




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt32(Enum) methode




```cpp
template<typename Enum,typename> static int32_t System::Convert::ToInt32(Enum value)
```

## Convert::ToInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) methode

Converteert de opgegeven ingepakte waarde naar een equivalente 32-bits integer-waarde.

```cpp
static int System::Convert::ToInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | De shared pointer naar het object dat de waarde inpakt die moet worden geconverteerd |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | De tekenreeks-opmaak die moet worden gebruikt als het type van de ingepakte waarde [String](../../string/) is |

### Retourwaarde

Een 32-bits integer-waarde gelijk aan de opgegeven ingepakte waarde

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
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)