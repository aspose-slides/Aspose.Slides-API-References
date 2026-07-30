---
title: ToChar()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Převod není podporován. Vždy vyvolá výjimku InvalidCastException.
type: docs
weight: 118
url: /cs/system/convert/tochar/
---
## Convert::ToChar(bool) metoda


Převod není podporován. Vždy vyvolá výjimku InvalidCastException.

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) metoda


Převádí zadané 8-bitové neznačkové celé číslo na ekvivalentní znak Unicode.

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) metoda


Převádí zadané 8-bitové znaménkové celé číslo na ekvivalentní znak Unicode.

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) metoda


Převádí zadané 16-bitové neznačkové celé číslo na ekvivalentní znak Unicode.

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) metoda


Převádí zadané 16-bitové znaménkové celé číslo na ekvivalentní znak Unicode.

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) metoda


Převádí zadané 32-bitové neznačkové celé číslo na ekvivalentní znak Unicode.

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) metoda


Převádí zadané 32-bitové znaménkové celé číslo na ekvivalentní znak Unicode.

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) metoda


Převádí zadané 64-bitové neznačkové celé číslo na ekvivalentní znak Unicode.

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) metoda


Převádí zadané 64-bitové znaménkové celé číslo na ekvivalentní znak Unicode.

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) metoda


Převod není podporován. Vždy vyvolá výjimku InvalidCastException.

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) metoda


Převod není podporován. Vždy vyvolá výjimku InvalidCastException.

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) metoda


Převod není podporován. Vždy vyvolá výjimku InvalidCastException.

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) metoda


Vrací zadaný znak Unicode.

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) metoda


Převod není podporován. Vždy vyvolá výjimku InvalidCastException.

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) metoda


Převádí první a jediný znak zadaného c-stringu na hodnotu char_t.

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const char_t * | C-string k převodu; očekává se, že c-string bude mít přesně 1 znak. |

### Návratová hodnota

První a jediný znak zadaného c-stringu, pokud má přesně 1 znak, jinak - 0

## Convert::ToChar(const String\&) metoda


Převádí první a jediný znak zadaného řetězce na hodnotu char_t.

```cpp
static char_t System::Convert::ToChar(const String &value)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu; očekává se, že řetězec bude mít přesně 1 znak. |

### Návratová hodnota

První a jediný znak zadaného řetězce, pokud má přesně 1 znak, jinak - 0

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda


Převádí první a jediný znak zadaného řetězce na hodnotu char_t.

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Řetězec k převodu; očekává se, že řetězec bude mít přesně 1 znak. |

### Návratová hodnota

První a jediný znak zadaného řetězce, pokud má přesně 1 znak, jinak - 0

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda


Převádí zadanou zapouzdřenou hodnotu na ekvivalentní znak Unicode.

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Sdílený ukazatel na objekt zapouzdřující hodnotu k převodu. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Formát řetězce, který se použije, pokud je typ zapouzdřené hodnoty [String](../../string/). |

### Návratová hodnota

Unicode znak ekvivalentní zadané zapouzdřené hodnotě.

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [Decimal](../../decimal/)
* Třída [DateTime](../../datetime/)
* Třída [String](../../string/)
* Třída [IFormatProvider](../../iformatprovider/)
* Třída [Object](../../object/)
* Struktura [Convert](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)