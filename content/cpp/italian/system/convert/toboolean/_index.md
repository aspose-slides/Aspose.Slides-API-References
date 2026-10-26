---
title: ToBoolean()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il valore booleano specificato.
type: docs
weight: 79
url: /it/system/convert/toboolean/
---
## Convert::ToBoolean(bool) metodo

Restituisce il valore booleano specificato.

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) metodo

Converte l'intero senza segno a 8 bit specificato in un valore booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) metodo

Converte l'intero con segno a 8 bit specificato in un valore booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) metodo

Converte l'intero senza segno a 16 bit specificato in un valore booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) metodo

Converte l'intero con segno a 16 bit specificato in un valore booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) metodo

Converte l'intero senza segno a 32 bit specificato in un valore booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) metodo

Converte l'intero con segno a 32 bit specificato in un valore booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) metodo

Converte l'intero senza segno a 64 bit specificato in un valore booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) metodo

Converte l'intero con segno a 64 bit specificato in un valore booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) metodo

Converte il numero float specificato in un valore booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) metodo

Converte il numero double specificato in un valore booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) metodo

Converte il numero decimale specificato in un valore booleano equivalente.

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) metodo

La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) metodo

La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) metodo

Converte la stringa nulla specificata nel valore booleano equivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```

### Valore restituito

False.

## Convert::ToBoolean(const char_t *) metodo

Converte la c-string specificata nel valore di tipo bool.

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const char_t * | La c-string da convertire |

### Valore restituito

True se la c-string specificata è uguale a "True" e false se la c-string specificata è uguale a "False".

## Convert::ToBoolean(const String\&) metodo

Converte la stringa specificata nel valore di tipo bool.

```cpp
static bool System::Convert::ToBoolean(const String &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |

### Valore restituito

True se la c-string specificata è uguale a "True" e false se la stringa specificata è uguale a "False".

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la stringa specificata nel valore di tipo bool.

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |

### Valore restituito

True se la c-string specificata è uguale a "True" e false se la stringa specificata è uguale a "False".

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte il valore boxed specificato in un valore booleano equivalente.

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Il puntatore condiviso all'oggetto che incapsula il valore da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Il formato stringa da usare se il tipo del valore boxed è [String](../../string/) |

### Valore restituito

Un valore booleano equivalente al valore boxed specificato

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Decimal](../../decimal/)
* Classe [DateTime](../../datetime/)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [Object](../../object/)
* Struttura [Convert](../)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)