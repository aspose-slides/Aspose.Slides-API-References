---
title: ToUInt64()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte il valore booleano specificato in un intero senza segno a 64 bit equivalente.
type: docs
weight: 196
url: /it/system/convert/touint64/
---
## Convert::ToUInt64(bool) metodo

Converte il valore booleano specificato in un intero senza segno a 64 bit equivalente.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(bool value)
```

## Convert::ToUInt64(uint8_t) metodo

Converte l'intero senza segno a 8 bit specificato in un intero senza segno a 64 bit equivalente.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint8_t value)
```

## Convert::ToUInt64(int8_t) metodo

Converte l'intero con segno a 8 bit specificato in un intero senza segno a 64 bit equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(int8_t value)
```

## Convert::ToUInt64(uint16_t) metodo

Converte l'intero senza segno a 16 bit specificato in un intero senza segno a 64 bit equivalente.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint16_t value)
```

## Convert::ToUInt64(int16_t) metodo

Converte l'intero con segno a 16 bit specificato in un intero senza segno a 64 bit equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(int16_t value)
```

## Convert::ToUInt64(uint32_t) metodo

Converte l'intero senza segno a 32 bit specificato in un intero senza segno a 64 bit equivalente.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint32_t value)
```

## Convert::ToUInt64(int32_t) metodo

Converte l'intero con segno a 32 bit specificato in un intero senza segno a 64 bit equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(int32_t value)
```

## Convert::ToUInt64(uint64_t) metodo

Restituisce l'intero senza segno a 64 bit specificato.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint64_t value)
```

## Convert::ToUInt64(int64_t) metodo

Converte l'intero con segno a 64 bit specificato in un intero senza segno a 64 bit equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(int64_t value)
```

## Convert::ToUInt64(float) metodo

Converte il numero float specificato in un intero senza segno a 64 bit equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(float value)
```

## Convert::ToUInt64(double) metodo

Converte il numero double specificato in un intero senza segno a 64 bit equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(double value)
```

## Convert::ToUInt64(const Decimal\&) metodo

Converte il numero decimale specificato in un intero senza segno a 64 bit equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(const Decimal &value)
```

## Convert::ToUInt64(char_t) metodo

Converte il carattere unicode specificato in un intero senza segno a 64 bit equivalente.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(char_t value)
```

## Convert::ToUInt64(DateTime) metodo

La conversione non è supportata. Sempre genera InvalidCastException.

```cpp
static uint64_t System::Convert::ToUInt64(DateTime value)
```

## Convert::ToUInt64(std::nullptr_t) metodo

Converte la stringa nulla specificata nel valore intero senza segno a 64 bit equivalente.

```cpp
static constexpr uint64_t System::Convert::ToUInt64(std::nullptr_t)
```


### Valore di ritorno

Zero.

## Convert::ToUInt64(const char_t *) metodo


Converte la c-string specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 64 bit equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(const char_t *value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const char_t * | La c-string da convertire |

### Valore di ritorno

Il valore intero senza segno a 64 bit uguale al numero rappresentato dalla c-string specificata

## Convert::ToUInt64(const String\&) metodo


Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 64 bit equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |

### Valore di ritorno

Il valore intero senza segno a 64 bit uguale al numero rappresentato dalla stringa specificata

## Convert::ToUInt64(const String\&, int) metodo


Converte la stringa specificata contenente la rappresentazione testuale di un numero nella base specificata nel valore intero senza segno a 64 bit equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, int from_base)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| from_base | int | La base del numero rappresentato dalla stringa |

### Valore di ritorno

Il valore intero senza segno a 64 bit uguale al numero rappresentato dalla stringa specificata

## Convert::ToUInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) metodo


Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 64 bit equivalente usando le informazioni di formattazione fornite.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni sul formato della stringa |

### Valore di ritorno

Il valore intero senza segno a 64 bit uguale al numero rappresentato dalla stringa specificata

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, std::nullptr_t) metodo




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, std::nullptr_t)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodo


Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 64 bit equivalente usando le informazioni di formattazione e lo stile numerico forniti.

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell'enum NumberStyles che specifica lo stile consentito della rappresentazione testuale di un numero |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni sul formato della stringa |

### Valore di ritorno

Il valore intero senza segno a 64 bit uguale al numero rappresentato dalla stringa specificata

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) metodo 




```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt64(Enum) metodo 




```cpp
template<typename Enum,typename> static uint64_t System::Convert::ToUInt64(Enum value)
```

## Convert::ToUInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metodo


Converte il valore incapsulato specificato nel valore intero senza segno a 64 bit equivalente.

```cpp
static uint64_t System::Convert::ToUInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Il puntatore condiviso all'oggetto che incapsula il valore da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Il formato della stringa da usare se il tipo del valore incapsulato è [String](../../string/) |

### Valore di ritorno

Un valore intero senza segno a 64 bit equivalente al valore incapsulato specificato

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