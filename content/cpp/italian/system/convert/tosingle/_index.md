---
title: ToSingle()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte il valore booleano specificato in un numero a virgola mobile a precisione singola equivalente.
type: docs
weight: 209
url: /it/system/convert/tosingle/
---
## Convert::ToSingle(bool) metodo

Converte il valore booleano specificato in un numero a virgola mobile a precisione singola equivalente.

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```

## Convert::ToSingle(uint8_t) metodo

Converte l’intero senza segno a 8 bit specificato in un numero a virgola mobile a precisione singola equivalente.

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```

## Convert::ToSingle(int8_t) metodo

Converte l’intero con segno a 8 bit specificato in un numero a virgola mobile a precisione singola equivalente.

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```

## Convert::ToSingle(uint16_t) metodo

Converte l’intero senza segno a 16 bit specificato in un numero a virgola mobile a precisione singola equivalente.

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```

## Convert::ToSingle(int16_t) metodo

Converte l’intero con segno a 16 bit specificato in un numero a virgola mobile a precisione singola equivalente.

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```

## Convert::ToSingle(uint32_t) metodo

Converte l’intero senza segno a 32 bit specificato in un numero a virgola mobile a precisione singola equivalente.

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```

## Convert::ToSingle(int32_t) metodo

Converte l’intero con segno a 32 bit specificato in un numero a virgola mobile a precisione singola equivalente.

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```

## Convert::ToSingle(uint64_t) metodo

Converte l’intero senza segno a 64 bit specificato in un numero a virgola mobile a precisione singola equivalente.

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```

## Convert::ToSingle(int64_t) metodo

Converte l’intero con segno a 64 bit specificato in un numero a virgola mobile a precisione singola equivalente.

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```

## Convert::ToSingle(float) metodo

Restituisce il numero float specificato.

```cpp
static constexpr float System::Convert::ToSingle(float value)
```

## Convert::ToSingle(double) metodo

Converte il numero double-precision specificato in un numero a virgola mobile a precisione singola equivalente.

```cpp
static constexpr float System::Convert::ToSingle(double value)
```

## Convert::ToSingle(const Decimal\&) metodo

Converte il numero decimale specificato in un numero a virgola mobile a precisione singola equivalente.

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```

## Convert::ToSingle(char_t) metodo

Conversione non supportata. Lancia sempre InvalidCastException.

```cpp
static float System::Convert::ToSingle(char_t value)
```

## Convert::ToSingle(DateTime) metodo

Conversione non supportata. Lancia sempre InvalidCastException.

```cpp
static float System::Convert::ToSingle(DateTime value)
```

## Convert::ToSingle(std::nullptr_t) metodo

Converte la stringa null specificata nel valore a virgola mobile a precisione singola equivalente.

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```

### Valore di ritorno

Zero.

## Convert::ToSingle(const char_t *) metodo

Converte la c-string contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente.

```cpp
static float System::Convert::ToSingle(const char_t *value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const char_t * | La c-string da convertire |

### Valore di ritorno

Il valore a virgola mobile a precisione singola uguale al numero rappresentato dalla c-string specificata

## Convert::ToSingle(const String\&) metodo

Converte la stringa contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente.

```cpp
static float System::Convert::ToSingle(const String &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |

### Valore di ritorno

Il valore a virgola mobile a precisione singola uguale al numero rappresentato dalla stringa specificata

## Convert::ToSingle(const String\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la stringa contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente usando le informazioni di formattazione fornite.

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni sul formato della stringa |

### Valore di ritorno

Il valore a virgola mobile a precisione singola uguale al numero rappresentato dalla stringa specificata

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodo

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, std::nullptr_t) metodo

```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la stringa contenente la rappresentazione testuale di un numero nel valore a virgola mobile a precisione singola equivalente usando le informazioni di formattazione fornite e lo stile numerico.

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell’enumerazione NumberStyles che specifica lo stile consentito della rappresentazione testuale del numero |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni sul formato della stringa |

### Valore di ritorno

Il valore a virgola mobile a precisione singola uguale al numero rappresentato dalla stringa specificata

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metodo

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, std::nullptr_t) metodo

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte il valore boxed specificato in un valore a virgola mobile a precisione singola.

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Il puntatore condiviso all'oggetto che incapsula il valore da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Il formato stringa da usare se il tipo del valore boxed è [String](../../string/) |

### Valore di ritorno

Un valore a virgola mobile a precisione singola equivalente al valore boxed specificato

## Vedi anche

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)