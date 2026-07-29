---
title: ToBoolean()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar det angivna boolska värdet.
type: docs
weight: 79
url: /sv/system/convert/toboolean/
---
## Convert::ToBoolean(bool) metod


Returnerar det angivna boolska värdet.

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) metod


Konverterar det angivna 8-bitars osignerade heltalet till ett motsvarande boolskt värde.

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) metod


Konverterar det angivna 8-bitars signerade heltalet till ett motsvarande boolskt värde.

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) metod


Konverterar det angivna 16-bitars osignerade heltalet till ett motsvarande boolskt värde.

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) metod


Konverterar det angivna 16-bitars signerade heltalet till ett motsvarande boolskt värde.

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) metod


Konverterar det angivna 32-bitars osignerade heltalet till ett motsvarande boolskt värde.

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) metod


Konverterar det angivna 32-bitars signerade heltalet till ett motsvarande boolskt värde.

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) metod


Konverterar det angivna 64-bitars osignerade heltalet till ett motsvarande boolskt värde.

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) metod


Konverterar det angivna 64-bitars signerade heltalet till ett motsvarande boolskt värde.

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) metod


Konverterar det angivna flyttalet till ett motsvarande boolskt värde.

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) metod


Konverterar det angivna dubbel-talet till ett motsvarande boolskt värde.

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) metod


Konverterar det angivna decimal-talet till ett motsvarande boolskt värde.

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) metod


Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) metod


Konvertering stöds inte. Kastar alltid InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) metod


Konverterar den angivna null-strängen till motsvarande boolska värde.

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```


### Returvärde

Falskt.

## Convert::ToBoolean(const char_t *) metod


Konverterar den angivna c-strängen till ett värde av typen bool.

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const char_t * | c-strängen att konvertera |

### Returvärde

Sant om den angivna c-strängen är lika med "True" och falskt om den angivna c-strängen är lika med "False".

## Convert::ToBoolean(const String\&) metod


Konverterar den angivna strängen till ett värde av typen bool.

```cpp
static bool System::Convert::ToBoolean(const String &value)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |

### Returvärde

Sant om den angivna strängen är lika med "True" och falskt om den angivna strängen är lika med "False".

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) metod


Konverterar den angivna strängen till ett värde av typen bool.

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen att konvertera |

### Returvärde

Sant om den angivna strängen är lika med "True" och falskt om den angivna strängen är lika med "False".

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metod


Konverterar det angivna inneslutna värdet till ett motsvarande boolskt värde.

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Den delade pekaren till objektet som packar värdet som ska konverteras |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Strängformatet som ska användas om den inneslutna värdestypen är [String](../../string/) |

### Returvärde

Ett boolskt värde som motsvarar det angivna inneslutna värdet

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [Decimal](../../decimal/)
* Klass [DateTime](../../datetime/)
* Klass [String](../../string/)
* Klass [IFormatProvider](../../iformatprovider/)
* Klass [Object](../../object/)
* Struct [Convert](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)