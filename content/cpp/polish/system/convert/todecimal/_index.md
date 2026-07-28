---
title: ToDecimal()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Konwertuje określoną wartość logiczną na równoważną liczbę dziesiętną.
type: docs
weight: 235
url: /pl/system/convert/todecimal/
---
## Convert::ToDecimal(bool) metoda

Konwertuje określoną wartość logiczną na równoważną liczbę dziesiętną.

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) metoda

Konwertuje określoną 8-bitową liczbę całkowitą bez znaku na równoważną liczbę dziesiętną.

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) metoda

Konwertuje określoną 8-bitową liczbę całkowitą ze znakiem na równoważną liczbę dziesiętną.

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) metoda

Konwertuje określoną 16-bitową liczbę całkowitą bez znaku na równoważną liczbę dziesiętną.

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) metoda

Konwertuje określoną 16-bitową liczbę całkowitą ze znakiem na równoważną liczbę dziesiętną.

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) metoda

Konwertuje określoną 32-bitową liczbę całkowitą bez znaku na równoważną liczbę dziesiętną.

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) metoda

Konwertuje określoną 32-bitową liczbę całkowitą ze znakiem na równoważną liczbę dziesiętną.

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) metoda

Konwertuje określoną 64-bitową liczbę całkowitą bez znaku na równoważną liczbę dziesiętną.

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) metoda

Konwertuje określoną 64-bitową liczbę całkowitą ze znakiem na równoważną liczbę dziesiętną.

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) metoda

Konwertuje określoną liczbę typu float na równoważną liczbę dziesiętną.

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) metoda

Konwertuje określoną liczbę typu double na równoważną liczbę dziesiętną.

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) metoda

Zwraca określoną liczbę dziesiętną.

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) metoda

Konwersja nie jest obsługiwana. Zawsze wyrzuca InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) metoda

Konwersja nie jest obsługiwana. Zawsze wyrzuca InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) metoda

Konwertuje określony null-string na równoważną wartość [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```

### Wartość zwracana

Zero.

## Convert::ToDecimal(const char_t *) metoda

Konwertuje określony c-string zawierający tekstową reprezentację liczby na równoważną wartość [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const char_t * | C-string do konwersji |

### Wartość zwracana

Wartość [Decimal](../../decimal/) równa liczbie reprezentowanej przez określony c-string

## Convert::ToDecimal(const String\&) metoda

Konwertuje określony string zawierający tekstową reprezentację liczby na równoważną wartość [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |

### Wartość zwracana

Wartość [Decimal](../../decimal/) równa liczbie reprezentowanej przez określony string

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje określony string zawierający tekstową reprezentację liczby na równoważną wartość [Decimal](../../decimal/) przy użyciu podanych informacji formatowania.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie ciągu |

### Wartość zwracana

Wartość [Decimal](../../decimal/) równa liczbie reprezentowanej przez określony string

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje określony string zawierający tekstową reprezentację liczby na równoważną wartość [Decimal](../../decimal/) przy użyciu podanych stylów liczby i informacji formatowania.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Ciąg znaków do konwersji |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Bitowa kombinacja wartości wyliczenia NumberStyles określająca dozwolone style tekstowej reprezentacji liczby |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Wskaźnik do obiektu zawierającego informacje o formacie ciągu |

### Wartość zwracana

Wartość [Decimal](../../decimal/) równa liczbie reprezentowanej przez określony string

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metoda

Konwertuje określoną opakowaną wartość na równoważną wartość [Decimal](../../decimal/).

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Współdzielony wskaźnik do obiektu opakowującego wartość do konwersji |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format ciągu używany, jeśli typ opakowanej wartości jest [String](../../string/) |

### Wartość zwracana

Wartość [Decimal](../../decimal/) równoważna określonej opakowanej wartości

## Zobacz także

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)