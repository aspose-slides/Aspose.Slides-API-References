---
title: ToDecimal()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte il valore booleano specificato in un numero decimale equivalente.
type: docs
weight: 235
url: /it/system/convert/todecimal/
---
## Convert::ToDecimal(bool) metodo

Converte il valore booleano specificato in un numero decimale equivalente.

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) metodo

Converte l'intero senza segno a 8 bit specificato in un numero decimale equivalente.

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) metodo

Converte l'intero con segno a 8 bit specificato in un numero decimale equivalente.

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) metodo

Converte l'intero senza segno a 16 bit specificato in un numero decimale equivalente.

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) metodo

Converte l'intero con segno a 16 bit specificato in un numero decimale equivalente.

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) metodo

Converte l'intero senza segno a 32 bit specificato in un numero decimale equivalente.

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) metodo

Converte l'intero con segno a 32 bit specificato in un numero decimale equivalente.

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) metodo

Converte l'intero senza segno a 64 bit specificato in un numero decimale equivalente.

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) metodo

Converte l'intero con segno a 64 bit specificato in un numero decimale equivalente.

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) metodo

Converte il numero in virgola mobile specificato in un numero decimale equivalente.

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) metodo

Converte il numero double specificato in un numero decimale equivalente.

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) metodo

Restituisce il numero decimale specificato.

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) metodo

La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) metodo

La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) metodo

Converte la stringa nulla specificata nel valore [Decimal](../../decimal/) equivalente.

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```

### Valore di ritorno

Zero.

## Convert::ToDecimal(const char_t *) metodo

Converte la c-string specificata contenente la rappresentazione testuale di un numero nel valore [Decimal](../../decimal/) equivalente.

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const char_t * | La c-string da convertire |

### Valore di ritorno

Il valore [Decimal](../../decimal/) pari al numero rappresentato dalla c-string specificata

## Convert::ToDecimal(const String\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore [Decimal](../../decimal/) equivalente.

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |

### Valore di ritorno

Il valore [Decimal](../../decimal/) pari al numero rappresentato dalla stringa specificata

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore [Decimal](../../decimal/) equivalente utilizzando le informazioni di formattazione fornite.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formattazione della stringa |

### Valore di ritorno

Il valore [Decimal](../../decimal/) pari al numero rappresentato dalla stringa specificata

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore [Decimal](../../decimal/) equivalente usando gli stili numerici specificati e le informazioni di formattazione.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell'enumerazione NumberStyles che specifica lo stile consentito della rappresentazione testuale di un numero |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formattazione della stringa |

### Valore di ritorno

Il valore [Decimal](../../decimal/) pari al numero rappresentato dalla stringa specificata

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte il valore boxed specificato in un valore [Decimal](../../decimal/) equivalente.

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Il puntatore condiviso all'oggetto che incapsula il valore da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Il formato della stringa da usare se il tipo del valore boxed è [String](../../string/) |

### Valore di ritorno

Un valore [Decimal](../../decimal/) equivalente al valore boxed specificato

## Vedi anche

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