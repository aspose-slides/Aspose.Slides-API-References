---
title: ToSingle()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar det angivna boolska värdet till ett motsvarande flyttal med enkel precision.
type: docs
weight: 209
url: /sv/system/convert/tosingle/
---
## Convert::ToSingle(bool) metod


Konverterar det angivna boolska värdet till ett motsvarande flyttal med enkel precision.

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```

## Convert::ToSingle(uint8_t) metod


Konverterar det angivna 8-bitars osignerade heltalet till ett motsvarande flyttal med enkel precision.

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```

## Convert::ToSingle(int8_t) metod


Konverterar det angivna 8-bitars signerade heltalet till ett motsvarande flyttal med enkel precision.

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```

## Convert::ToSingle(uint16_t) metod


Konverterar det angivna 16-bitars osignerade heltalet till ett motsvarande flyttal med enkel precision.

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```

## Convert::ToSingle(int16_t) metod


Konverterar det angivna 16-bitars signerade heltalet till ett motsvarande flyttal med enkel precision.

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```

## Convert::ToSingle(uint32_t) metod


Konverterar det angivna 32-bitars osignerade heltalet till ett motsvarande flyttal med enkel precision.

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```

## Convert::ToSingle(int32_t) metod


Konverterar det angivna 32-bitars signerade heltalet till ett motsvarande flyttal med enkel precision.

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```

## Convert::ToSingle(uint64_t) metod


Konverterar det angivna 64-bitars osignerade heltalet till ett motsvarande flyttal med enkel precision.

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```

## Convert::ToSingle(int64_t) metod


Konverterar det angivna 64-bitars signerade heltalet till ett motsvarande flyttal med enkel precision.

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```

## Convert::ToSingle(float) metod


Returnerar det angivna float-värdet.

```cpp
static constexpr float System::Convert::ToSingle(float value)
```

## Convert::ToSingle(double) metod


Konverterar det angivna dubbelprecision-värdet till ett motsvarande flyttal med enkel precision.

```cpp
static constexpr float System::Convert::ToSingle(double value)
```

## Convert::ToSingle(const Decimal\&) metod


Konverterar det angivna decimalvärdet till ett motsvarande flyttal med enkel precision.

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```

## Convert::ToSingle(char_t) metod


Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static float System::Convert::ToSingle(char_t value)
```

## Convert::ToSingle(DateTime) metod


Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static float System::Convert::ToSingle(DateTime value)
```

## Convert::ToSingle(std::nullptr_t) metod


Konverterar den angivna null-strängen till motsvarande flyttal med enkel precision.

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```


### Returvärde

Noll.

## Convert::ToSingle(const char_t *) metod


Konverterar den angivna c-strängen som innehåller talets teckenrepresentation till motsvarande flyttal med enkel precision.

```cpp
static float System::Convert::ToSingle(const char_t *value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const char_t * | c-strängen som ska konverteras |

### Returvärde

Flyttalet med enkel precision som motsvarar det tal som representeras av den angivna c-strängen

## Convert::ToSingle(const String\&) metod


Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande flyttal med enkel precision.

```cpp
static float System::Convert::ToSingle(const String &value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska konverteras |

### Returvärde

Flyttalet med enkel precision som motsvarar det tal som representeras av den angivna strängen

## Convert::ToSingle(const String\&, const SharedPtr\<IFormatProvider\>\&) metod


Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande flyttal med enkel precision med hjälp av den angivna formateringsinformationen.

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska konverteras |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller formateringsinformationen för strängen |

### Returvärde

Flyttalet med enkel precision som motsvarar det tal som representeras av den angivna strängen

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, std::nullptr_t) metod




```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metod


Konverterar den angivna strängen som innehåller talets teckenrepresentation till motsvarande flyttal med enkel precision med hjälp av den angivna formateringsinformationen och talstilen.

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som ska konverteras |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden från enum-typen NumberStyles som anger tillåten stil för talets teckenrepresentation |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller formateringsinformationen för strängen |

### Returvärde

Flyttalet med enkel precision som motsvarar det tal som representeras av den angivna strängen

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metod




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metod




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, std::nullptr_t) metod 




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metod


Konverterar det angivna boxed-värdet till ett flyttal med enkel precision.

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Den delade pekaren till objektet som kapslar in värdet som ska konverteras |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Strängformatet som ska användas om den boxed-typen är [String](../../string/) |

### Returvärde

Ett flyttal med enkel precision som motsvarar det angivna boxed-värdet

## Se även

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [Decimal](../../decimal/)
* Klass [DateTime](../../datetime/)
* Klass [String](../../string/)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Klass [Object](../../object/)
* Struktur [Convert](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)