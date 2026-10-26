---
title: ToBoolean()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de opgegeven booleaanse waarde.
type: docs
weight: 79
url: /nl/system/convert/toboolean/
---
## Convert::ToBoolean(bool) methode


Retourneert de opgegeven booleaanse waarde.

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) methode


Converteert het opgegeven 8-bit unsigned integer naar een equivalente booleaanse waarde.

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) methode


Converteert het opgegeven 8-bit signed integer naar een equivalente booleaanse waarde.

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) methode


Converteert het opgegeven 16-bit unsigned integer naar een equivalente booleaanse waarde.

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) methode


Converteert het opgegeven 16-bit signed integer naar een equivalente booleaanse waarde.

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) methode


Converteert het opgegeven 32-bit unsigned integer naar een equivalente booleaanse waarde.

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) methode


Converteert het opgegeven 32-bit signed integer naar een equivalente booleaanse waarde.

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) methode


Converteert het opgegeven 64-bit unsigned integer naar een equivalente booleaanse waarde.

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) methode


Converteert het opgegeven 64-bit signed integer naar een equivalente booleaanse waarde.

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) methode


Converteert het opgegeven float-getal naar een equivalente booleaanse waarde.

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) methode


Converteert het opgegeven double-getal naar een equivalente booleaanse waarde.

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) methode


Converteert het opgegeven decimale getal naar een equivalente booleaanse waarde.

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) methode


Conversie wordt niet ondersteund. Gooit altijd InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) methode


Conversie wordt niet ondersteund. Gooit altijd InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) methode


Converteert de opgegeven null-string naar de equivalente booleaanse waarde.

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```


### Retourwaarde

False.

## Convert::ToBoolean(const char_t *) methode


Converteert de opgegeven c-string naar een waarde van het type bool.

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const char_t * | De c-string om te converteren |

### Retourwaarde

True if the specified c-string is equal to "True" and false if the specified c-string is equal to "False".

## Convert::ToBoolean(const String\&) methode


Converteert de opgegeven string naar een waarde van het type bool.

```cpp
static bool System::Convert::ToBoolean(const String &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |

### Retourwaarde

True if the specified c-string is equal to "True" and false if the specified string is equal to "False".

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven string naar een waarde van het type bool.

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren |

### Retourwaarde

True if the specified c-string is equal to "True" and false if the specified string is equal to "False".

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) methode


Converteert de opgegeven boxed value naar een equivalente booleaanse waarde.

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | De shared pointer naar het object dat de te converteren waarde bevat |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | De string-indeling die moet worden gebruikt als het type van de boxed value [String](../../string/) is |

### Retourwaarde

An boolean value equivalent to the specified boxed value

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)