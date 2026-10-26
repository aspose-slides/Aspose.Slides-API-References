---
title: ToChar()
second_title: Aspose.Slides för C++ API-referens
description: Konvertering stöds inte. Kastar alltid InvalidCastException.
type: docs
weight: 118
url: /sv/system/convert/tochar/
---
## Convert::ToChar(bool) metod


Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) metod


Konverterar det angivna 8-bit osignerade heltalet till ett motsvarande unicode-tecken.

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) metod


Konverterar det angivna 8-bit signerade heltalet till ett motsvarande unicode-tecken.

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) metod


Konverterar det angivna 16-bit osignerade heltalet till ett motsvarande unicode-tecken.

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) metod


Konverterar det angivna 16-bit signerade heltalet till ett motsvarande unicode-tecken.

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) metod


Konverterar det angivna 32-bit osignerade heltalet till ett motsvarande unicode-tecken.

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) metod


Konverterar det angivna 32-bit signerade heltalet till ett motsvarande unicode-tecken.

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) metod


Konverterar det angivna 64-bit osignerade heltalet till ett motsvarande unicode-tecken.

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) metod


Konverterar det angivna 64-bit signerade heltalet till ett motsvarande unicode-tecken.

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) metod


Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) metod


Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) metod


Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) metod


Returnerar det angivna unicode-tecknet.

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) metod


Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) metod


Konverterar det första och enda tecknet i den angivna c-stringen till ett char_t-värde.

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const char_t * | c-stringen att konvertera; det förväntas att c-stringen är exakt 1 tecken lång. |

### Returvärde

Det första och enda tecknet i den angivna c-stringen om den är exakt 1 tecken lång, annars - 0

## Convert::ToChar(const String\&) metod


Konverterar det första och enda tecknet i den angivna strängen till ett char_t-värde.

```cpp
static char_t System::Convert::ToChar(const String &value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera; det förväntas att strängen är exakt 1 tecken lång. |

### Returvärde

Det första och enda tecknet i den angivna strängen om den är exakt 1 tecken lång, annars - 0

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) metod


Konverterar det första och enda tecknet i den angivna strängen till ett char_t-värde.

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera; det förväntas att strängen är exakt 1 tecken lång. |

### Returvärde

Det första och enda tecknet i den angivna strängen om den är exakt 1 tecken lång, annars - 0

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metod


Konverterar det specificerade inneslutna värdet till motsvarande unicode-tecken.

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Den delade pekaren till objektet som omsluter värdet att konvertera. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Strängformatet att använda om den inneslutna värdestypen är [String](../../string/). |

### Returvärde

Ett unicode-tecken som motsvarar det specificerade inneslutna värdet.

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)