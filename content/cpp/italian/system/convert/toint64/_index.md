---
title: ToInt64()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte il valore booleano specificato in un intero con segno a 64-bit equivalente.
type: docs
weight: 183
url: /it/system/convert/toint64/
---
## Convert::ToInt64(bool) metodo

Converte il valore booleano specificato in un intero con segno a 64-bit equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(bool value)
```

## Convert::ToInt64(uint8_t) metodo

Converte l’intero senza segno a 8-bit specificato in un intero con segno a 64-bit equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint8_t value)
```

## Convert::ToInt64(int8_t) metodo

Converte l’intero con segno a 8-bit specificato in un intero con segno a 64-bit equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(int8_t value)
```

## Convert::ToInt64(uint16_t) metodo

Converte l’intero senza segno a 16-bit specificato in un intero con segno a 64-bit equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint16_t value)
```

## Convert::ToInt64(int16_t) metodo

Converte l’intero con segno a 16-bit specificato in un intero con segno a 64-bit equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(int16_t value)
```

## Convert::ToInt64(uint32_t) metodo

Converte l’intero senza segno a 32-bit specificato in un intero con segno a 64-bit equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint32_t value)
```

## Convert::ToInt64(int32_t) metodo

Converte l’intero con segno a 32-bit specificato in un intero con segno a 64-bit equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(int32_t value)
```

## Convert::ToInt64(uint64_t) metodo

Converte l’intero senza segno a 64-bit specificato in un intero con segno a 64-bit equivalente.

```cpp
static int64_t System::Convert::ToInt64(uint64_t value)
```

## Convert::ToInt64(int64_t) metodo

Restituisce l’intero con segno a 64-bit specificato.

```cpp
static constexpr int64_t System::Convert::ToInt64(int64_t value)
```

## Convert::ToInt64(float) metodo

Converte il numero a virgola mobile specificato in un intero con segno a 64-bit equivalente.

```cpp
static int64_t System::Convert::ToInt64(float value)
```

## Convert::ToInt64(double) metodo

Converte il numero double specificato in un intero con segno a 64-bit equivalente.

```cpp
static int64_t System::Convert::ToInt64(double value)
```

## Convert::ToInt64(const Decimal\&) metodo

Converte il numero decimale specificato in un intero con segno a 64-bit equivalente.

```cpp
static int64_t System::Convert::ToInt64(const Decimal &value)
```

## Convert::ToInt64(char_t) metodo

Converte il carattere Unicode specificato in un intero con segno a 64-bit equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(char_t value)
```

## Convert::ToInt64(DateTime) metodo

Conversione non supportata. Lancia sempre InvalidCastException.

```cpp
static int64_t System::Convert::ToInt64(DateTime value)
```

## Convert::ToInt64(std::nullptr_t) metodo

Converte la stringa nulla specificata nel valore intero a 64-bit equivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(std::nullptr_t)
```

### Valore restituito

Zero.

## Convert::ToInt64(const char_t *) metodo

Converte la c-string contenente la rappresentazione testuale di un numero nel valore intero a 64-bit equivalente.

```cpp
static int64_t System::Convert::ToInt64(const char_t *value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const char_t * | La stringa C da convertire |

### Valore restituito

Il valore intero a 64-bit pari al numero rappresentato dalla c-string specificata

## Convert::ToInt64(const String\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero a 64-bit equivalente.

```cpp
static int64_t System::Convert::ToInt64(const String &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |

### Valore restituito

Il valore intero a 64-bit pari al numero rappresentato dalla stringa specificata

## Convert::ToInt64(const String\&, int) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nella base specificata nel valore intero a 64-bit equivalente.

```cpp
static int64_t System::Convert::ToInt64(const String &value, int from_base)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| from_base | int | La base del numero rappresentato dalla stringa |

### Valore restituito

Il valore intero a 64-bit pari al numero rappresentato dalla stringa specificata

## Convert::ToInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero a 64-bit equivalente utilizzando le informazioni di formattazione fornite.

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni sul formato della stringa |

### Valore restituito

Il valore intero a 64-bit pari al numero rappresentato dalla stringa specificata

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodo

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, std::nullptr_t) metodo

```cpp
static int64_t System::Convert::ToInt64(const String &value, std::nullptr_t)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero a 64-bit equivalente utilizzando le informazioni di formattazione e lo stile numerico forniti.

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell’enum NumberStyles che specifica lo stile consentito della rappresentazione testuale del numero |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni sul formato della stringa |

### Valore restituito

Il valore intero a 64-bit pari al numero rappresentato dalla stringa specificata

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metodo

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) metodo

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt64(Enum) metodo

```cpp
template<typename Enum,typename> static int64_t System::Convert::ToInt64(Enum value)
```

## Convert::ToInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte il valore boxed specificato in un valore intero a 64-bit equivalente.

```cpp
static int64_t System::Convert::ToInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Il puntatore condiviso all’oggetto che incapsula il valore da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Il formato della stringa da usare se il tipo del valore boxed è [String](../../string/) |

### Valore restituito

Un valore intero a 64-bit equivalente al valore boxed specificato

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
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)