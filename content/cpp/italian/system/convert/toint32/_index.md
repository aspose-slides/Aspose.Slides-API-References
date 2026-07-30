---
title: ToInt32()
second_title: Riferimento API Aspose.Slides per C++
description: Converte il valore booleano specificato in un intero con segno a 32-bit equivalente.
type: docs
weight: 157
url: /it/system/convert/toint32/
---
## Convert::ToInt32(bool) metodo

Converte il valore booleano specificato in un intero con segno a 32 bit equivalente.

```cpp
static constexpr int System::Convert::ToInt32(bool value)
```

## Convert::ToInt32(uint8_t) metodo

Converte l’intero non firmato a 8 bit specificato in un intero con segno a 32 bit equivalente.

```cpp
static constexpr int System::Convert::ToInt32(uint8_t value)
```

## Convert::ToInt32(int8_t) metodo

Converte l’intero con segno a 8 bit specificato in un intero con segno a 32 bit equivalente.

```cpp
static constexpr int System::Convert::ToInt32(int8_t value)
```

## Convert::ToInt32(uint16_t) metodo

Converte l’intero non firmato a 16 bit specificato in un intero con segno a 32 bit equivalente.

```cpp
static constexpr int System::Convert::ToInt32(uint16_t value)
```

## Convert::ToInt32(int16_t) metodo

Converte l’intero con segno a 16 bit specificato in un intero con segno a 32 bit equivalente.

```cpp
static constexpr int System::Convert::ToInt32(int16_t value)
```

## Convert::ToInt32(uint32_t) metodo

Converte l’intero non firmato a 32 bit specificato in un intero con segno a 32 bit equivalente.

```cpp
static int System::Convert::ToInt32(uint32_t value)
```

## Convert::ToInt32(int32_t) metodo

Restituisce l’intero con segno a 32 bit specificato.

```cpp
static constexpr int System::Convert::ToInt32(int32_t value)
```

## Convert::ToInt32(uint64_t) metodo

Converte l’intero non firmato a 64 bit specificato in un intero con segno a 32 bit equivalente.

```cpp
static int System::Convert::ToInt32(uint64_t value)
```

## Convert::ToInt32(int64_t) metodo

Converte l’intero con segno a 64 bit specificato in un intero con segno a 32 bit equivalente.

```cpp
static int System::Convert::ToInt32(int64_t value)
```

## Convert::ToInt32(float) metodo

Converte il numero a virgola mobile specificato in un intero con segno a 32 bit equivalente.

```cpp
static int System::Convert::ToInt32(float value)
```

## Convert::ToInt32(double) metodo

Converte il numero double specificato in un intero con segno a 32 bit equivalente.

```cpp
static int System::Convert::ToInt32(double value)
```

## Convert::ToInt32(const Decimal\&) metodo

Converte il numero decimale specificato in un intero con segno a 32 bit equivalente.

```cpp
static int System::Convert::ToInt32(const Decimal &value)
```

## Convert::ToInt32(char_t) metodo

Converte il carattere Unicode specificato in un intero con segno a 32 bit equivalente.

```cpp
static constexpr int System::Convert::ToInt32(char_t value)
```

## Convert::ToInt32(DateTime) metodo

La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static int System::Convert::ToInt32(DateTime value)
```

## Convert::ToInt32(std::nullptr_t) metodo

Converte la stringa nulla specificata nel valore intero a 32 bit equivalente.

```cpp
static constexpr int System::Convert::ToInt32(std::nullptr_t)
```

### Valore di ritorno

Zero.

## Convert::ToInt32(const char_t *) metodo

Converte la c-string specificata contenente la rappresentazione testuale di un numero nel valore intero a 32 bit equivalente.

```cpp
static int System::Convert::ToInt32(const char_t *value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const char_t * | La c-string da convertire |

### Valore di ritorno

Il valore intero a 32 bit uguale al numero rappresentato dalla c-string specificata

## Convert::ToInt32(const String\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero a 32 bit equivalente.

```cpp
static int System::Convert::ToInt32(const String &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |

### Valore di ritorno

Il valore intero a 32 bit uguale al numero rappresentato dalla stringa specificata

## Convert::ToInt32(const String\&, int) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nella base specificata nel valore intero a 32 bit equivalente.

```cpp
static int System::Convert::ToInt32(const String &value, int from_base)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| from_base | int | La base del numero rappresentato dalla stringa |

### Valore di ritorno

Il valore intero a 32 bit uguale al numero rappresentato dalla stringa specificata

## Convert::ToInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero a 32 bit equivalente usando le informazioni di formattazione fornite.

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formattazione della stringa |

### Valore di ritorno

Il valore intero a 32 bit uguale al numero rappresentato dalla stringa specificata

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodo

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, std::nullptr_t) metodo

```cpp
static int System::Convert::ToInt32(const String &value, std::nullptr_t)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero a 32 bit equivalente usando le informazioni di formattazione e lo stile numerico forniti.

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell’enumerazione NumberStyles che specifica lo stile consentito della rappresentazione testuale di un numero |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formattazione della stringa |

### Valore di ritorno

Il valore intero a 32 bit uguale al numero rappresentato dalla stringa specificata

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metodo

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) metodo

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt32(Enum) metodo

```cpp
template<typename Enum,typename> static int32_t System::Convert::ToInt32(Enum value)
```

## Convert::ToInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte il valore boxed specificato in un valore intero a 32 bit equivalente.

```cpp
static int System::Convert::ToInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Il puntatore condiviso all’oggetto che contiene il valore da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Il formato di stringa da usare se il tipo del valore boxed è [String](../../string/) |

### Valore di ritorno

Un valore intero a 32 bit equivalente al valore boxed specificato

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