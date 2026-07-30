---
title: ToBoolean()
second_title: Reference API Aspose.Slides pro C++
description: Vrací zadanou hodnotu typu boolean.
type: docs
weight: 79
url: /cs/system/convert/toboolean/
---
## Convert::ToBoolean(bool) metoda


Vrací zadanou hodnotu typu boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) metoda


Převede zadané 8-bitové neznačené celé číslo na ekvivalentní hodnotu typu boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) metoda


Převede zadané 8-bitové podepsané celé číslo na ekvivalentní hodnotu typu boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) metoda


Převede zadané 16-bitové neznačené celé číslo na ekvivalentní hodnotu typu boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) metoda


Převede zadané 16-bitové podepsané celé číslo na ekvivalentní hodnotu typu boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) metoda


Převede zadané 32-bitové neznačené celé číslo na ekvivalentní hodnotu typu boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) metoda


Převede zadané 32-bitové podepsané celé číslo na ekvivalentní hodnotu typu boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) metoda


Převede zadané 64-bitové neznačené celé číslo na ekvivalentní hodnotu typu boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) metoda


Převede zadané 64-bitové podepsané celé číslo na ekvivalentní hodnotu typu boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) metoda


Převede zadané číslo typu float na ekvivalentní hodnotu typu boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) metoda


Převede zadané číslo typu double na ekvivalentní hodnotu typu boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) metoda


Převede zadané desetinné číslo na ekvivalentní hodnotu typu boolean.

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) metoda


Převod není podporován. Vždy vyhodí InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) metoda


Převod není podporován. Vždy vyhodí InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) metoda


Převede zadaný null-string na ekvivalentní hodnotu typu boolean.

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```


### Návratová hodnota

False.

## Convert::ToBoolean(const char_t *) metoda


Převede zadaný c-string na hodnotu typu bool.

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const char_t * | C-string k převodu |

### Návratová hodnota

True pokud je zadaný c-string roven "True" a false pokud je zadaný c-string roven "False".

## Convert::ToBoolean(const String\&) metoda


Převede zadaný řetězec na hodnotu typu bool.

```cpp
static bool System::Convert::ToBoolean(const String &value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |

### Návratová hodnota

True pokud je zadaný c-string roven "True" a false pokud je zadaný řetězec roven "False".

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Převede zadaný řetězec na hodnotu typu bool.

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu |

### Návratová hodnota

True pokud je zadaný c-string roven "True" a false pokud je zadaný řetězec roven "False".

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda


Převede zadanou zabalenou hodnotu na ekvivalentní hodnotu typu boolean.

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Sdílený ukazatel na objekt zabalený pro převod |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formát řetězce, který se použije, pokud je typ zabalené hodnoty [String](../../string/) |

### Návratová hodnota

Hodnota typu boolean ekvivalentní zadané zabalené hodnotě

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)