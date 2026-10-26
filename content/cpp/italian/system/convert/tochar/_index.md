---
title: ToChar()
second_title: Riferimento API di Aspose.Slides per C++
description: La conversione non è supportata. Lancia sempre InvalidCastException.
type: docs
weight: 118
url: /it/system/convert/tochar/
---
## Convert::ToChar(bool) metodo

La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) metodo

Converte l'intero senza segno a 8-bit specificato in un carattere unicode equivalente.

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) metodo

Converte l'intero con segno a 8-bit specificato in un carattere unicode equivalente.

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) metodo

Converte l'intero senza segno a 16-bit specificato in un carattere unicode equivalente.

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) metodo

Converte l'intero con segno a 16-bit specificato in un carattere unicode equivalente.

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) metodo

Converte l'intero senza segno a 32-bit specificato in un carattere unicode equivalente.

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) metodo

Converte l'intero con segno a 32-bit specificato in un carattere unicode equivalente.

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) metodo

Converte l'intero senza segno a 64-bit specificato in un carattere unicode equivalente.

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) metodo

Converte l'intero con segno a 64-bit specificato in un carattere unicode equivalente.

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) metodo

La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) metodo

La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) metodo

La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) metodo

Restituisce il carattere unicode specificato.

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) metodo

La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) metodo

Converte il primo e unico carattere della c-string specificata in un valore char_t.

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const char_t * | La c-string da convertire; ci si aspetta che la c-string sia esattamente 1 carattere lunga. |

### Valore di ritorno

Il primo e unico carattere della c-string specificata se è esattamente lunga 1 carattere, altrimenti - 0

## Convert::ToChar(const String\&) metodo

Converte il primo e unico carattere della stringa specificata in un valore char_t.

```cpp
static char_t System::Convert::ToChar(const String &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire; ci si aspetta che la stringa sia esattamente 1 carattere lunga. |

### Valore di ritorno

Il primo e unico carattere della stringa specificata se è esattamente lunga 1 carattere, altrimenti - 0

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte il primo e unico carattere della stringa specificata in un valore char_t.

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire; ci si aspetta che la stringa sia esattamente 1 carattere lunga. |

### Valore di ritorno

Il primo e unico carattere della stringa specificata se è esattamente lunga 1 carattere, altrimenti - 0

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte il valore boxed specificato in un carattere unicode equivalente.

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Il puntatore condiviso all'oggetto che incapsula il valore da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Il formato stringa da usare se il tipo del valore boxed è [String](../../string/) |

### Valore di ritorno

Un carattere unicode equivalente al valore boxed specificato

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)