---
title: ToUInt32()
second_title: Riferimento API Aspose.Slides per C++
description: Converte il valore booleano specificato in un intero senza segno a 32 bit equivalente.
type: docs
weight: 170
url: /it/system/convert/touint32/
---
## Convert::ToUInt32(bool) metodo

Converte il valore booleano specificato in un intero senza segno a 32 bit equivalente.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(bool value)
```

## Convert::ToUInt32(uint8_t) metodo

Converte l'intero senza segno a 8 bit specificato in un intero senza segno a 32 bit equivalente.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint8_t value)
```

## Convert::ToUInt32(int8_t) metodo

Converte l'intero con segno a 8 bit specificato in un intero senza segno a 32 bit equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(int8_t value)
```

## Convert::ToUInt32(uint16_t) metodo

Converte l'intero senza segno a 16 bit specificato in un intero senza segno a 32 bit equivalente.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint16_t value)
```

## Convert::ToUInt32(int16_t) metodo

Converte l'intero con segno a 16 bit specificato in un intero senza segno a 32 bit equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(int16_t value)
```

## Convert::ToUInt32(uint32_t) metodo

Restituisce l'intero senza segno a 32 bit specificato.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint32_t value)
```

## Convert::ToUInt32(int32_t) metodo

Converte l'intero con segno a 32 bit specificato in un intero senza segno a 32 bit equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(int32_t value)
```

## Convert::ToUInt32(uint64_t) metodo

Converte l'intero senza segno a 64 bit specificato in un intero senza segno a 32 bit equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(uint64_t value)
```

## Convert::ToUInt32(int64_t) metodo

Converte l'intero con segno a 64 bit specificato in un intero senza segno a 32 bit equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(int64_t value)
```

## Convert::ToUInt32(float) metodo

Converte il numero float specificato in un intero senza segno a 32 bit equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(float value)
```

## Convert::ToUInt32(double) metodo

Converte il numero double specificato in un intero senza segno a 32 bit equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(double value)
```

## Convert::ToUInt32(const Decimal\&) metodo

Converte il numero decimale specificato in un intero senza segno a 32 bit equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(const Decimal &value)
```

## Convert::ToUInt32(char_t) metodo

Converte il carattere Unicode specificato in un intero senza segno a 32 bit equivalente.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(char_t value)
```

## Convert::ToUInt32(DateTime) metodo

La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static uint32_t System::Convert::ToUInt32(DateTime value)
```

## Convert::ToUInt32(std::nullptr_t) metodo

Converte la stringa nullo specificata nel valore intero senza segno a 32 bit equivalente.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(std::nullptr_t)
```

### Valore di ritorno

Zero.

## Convert::ToUInt32(const char_t *) metodo

Converte la c-string specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 32 bit equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(const char_t *value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const char_t * | La c-string da convertire |

### Valore di ritorno

Il valore intero senza segno a 32 bit uguale al numero rappresentato dalla c-string specificata

## Convert::ToUInt32(const String\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 32 bit equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |

### Valore di ritorno

Il valore intero senza segno a 32 bit uguale al numero rappresentato dalla stringa specificata

## Convert::ToUInt32(const String\&, int) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nella base specificata nel valore intero senza segno a 32 bit equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, int from_base)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| from_base | int | La base del numero rappresentato dalla stringa |

### Valore di ritorno

Il valore intero senza segno a 32 bit uguale al numero rappresentato dalla stringa specificata

## Convert::ToUInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 32 bit equivalente utilizzando le informazioni di formattazione fornite.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formattazione della stringa |

### Valore di ritorno

Il valore intero senza segno a 32 bit uguale al numero rappresentato dalla stringa specificata

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, std::nullptr_t) metodo




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, std::nullptr_t)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 32 bit equivalente utilizzando le informazioni di formattazione fornite e lo stile numerico.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell'enum NumberStyles che specifica lo stile consentito della rappresentazione testuale di un numero |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formattazione della stringa |

### Valore di ritorno

Il valore intero senza segno a 32 bit uguale al numero rappresentato dalla stringa specificata

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo 




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) metodo 




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt32(Enum) metodo 




```cpp
template<typename Enum,typename> static uint32_t System::Convert::ToUInt32(Enum value)
```

## Convert::ToUInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte il valore boxed specificato nel valore intero senza segno a 32 bit equivalente.

```cpp
static uint32_t System::Convert::ToUInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Il puntatore condiviso all'oggetto che incapsula il valore da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Il formato di stringa da utilizzare se il tipo del valore boxed è [String](../../string/) |

### Valore di ritorno

Un valore intero senza segno a 32 bit equivalente al valore boxed specificato

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