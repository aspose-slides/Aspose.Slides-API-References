---
title: ToSByte()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte il valore booleano specificato in un intero con segno a 8 bit equivalente.
type: docs
weight: 105
url: /it/system/convert/tosbyte/
---
## Convert::ToSByte(bool) metodo

Converte il valore booleano specificato in un intero con segno a 8 bit equivalente.

```cpp
static constexpr int8_t System::Convert::ToSByte(bool value)
```
## Convert::ToSByte(uint8_t) metodo

Converte l’intero non firmato a 8 bit specificato in un intero con segno a 8 bit equivalente.

```cpp
static int8_t System::Convert::ToSByte(uint8_t value)
```
## Convert::ToSByte(int8_t) metodo

Restituisce l’intero con segno a 8 bit specificato.

```cpp
static constexpr int8_t System::Convert::ToSByte(int8_t value)
```
## Convert::ToSByte(uint16_t) metodo

Converte l’intero non firmato a 16 bit specificato in un intero con segno a 8 bit equivalente.

```cpp
static int8_t System::Convert::ToSByte(uint16_t value)
```
## Convert::ToSByte(int16_t) metodo

Converte l’intero con segno a 16 bit specificato in un intero con segno a 8 bit equivalente.

```cpp
static int8_t System::Convert::ToSByte(int16_t value)
```
## Convert::ToSByte(uint32_t) metodo

Converte l’intero non firmato a 32 bit specificato in un intero con segno a 8 bit equivalente.

```cpp
static int8_t System::Convert::ToSByte(uint32_t value)
```
## Convert::ToSByte(int32_t) metodo

Converte l’intero con segno a 32 bit specificato in un intero con segno a 8 bit equivalente.

```cpp
static int8_t System::Convert::ToSByte(int32_t value)
```
## Convert::ToSByte(uint64_t) metodo

Converte l’intero non firmato a 64 bit specificato in un intero con segno a 8 bit equivalente.

```cpp
static int8_t System::Convert::ToSByte(uint64_t value)
```
## Convert::ToSByte(int64_t) metodo

Converte l’intero con segno a 64 bit specificato in un intero con segno a 8 bit equivalente.

```cpp
static int8_t System::Convert::ToSByte(int64_t value)
```
## Convert::ToSByte(float) metodo

Converte il numero in virgola mobile specificato in un intero con segno a 8 bit equivalente.

```cpp
static int8_t System::Convert::ToSByte(float value)
```
## Convert::ToSByte(double) metodo

Converte il numero double specificato in un intero con segno a 8 bit equivalente.

```cpp
static int8_t System::Convert::ToSByte(double value)
```
## Convert::ToSByte(const Decimal\&) metodo

Converte il numero decimale specificato in un intero con segno a 8 bit equivalente.

```cpp
static int8_t System::Convert::ToSByte(const Decimal &value)
```
## Convert::ToSByte(char_t) metodo

Converte il carattere unicode specificato in un intero con segno a 8 bit equivalente.

```cpp
static int8_t System::Convert::ToSByte(char_t value)
```
## Convert::ToSByte(DateTime) metodo

La conversione non è supportata. Genera sempre InvalidCastException.

```cpp
static int8_t System::Convert::ToSByte(DateTime value)
```
## Convert::ToSByte(std::nullptr_t) metodo

Converte la stringa null specificata nel valore intero a 8 bit equivalente.

```cpp
static constexpr int8_t System::Convert::ToSByte(std::nullptr_t)
```

### Valore restituito

Zero.

## Convert::ToSByte(const char_t *) metodo

Converte la c-stringa contenente la rappresentazione testuale di un numero nel valore intero a 8 bit equivalente.

```cpp
static int8_t System::Convert::ToSByte(const char_t *value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const char_t * | La c-stringa da convertire |

### Valore restituito

Il valore intero a 8 bit pari al numero rappresentato dalla c-stringa specificata

## Convert::ToSByte(const String\&) metodo

Converte la stringa contenente la rappresentazione testuale di un numero nel valore intero a 8 bit equivalente.

```cpp
static int8_t System::Convert::ToSByte(const String &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |

### Valore restituito

Il valore intero a 8 bit pari al numero rappresentato dalla stringa specificata

## Convert::ToSByte(const String\&, int) metodo

Converte la stringa contenente la rappresentazione testuale di un numero nella base specificata nel valore intero a 8 bit equivalente.

```cpp
static int8_t System::Convert::ToSByte(const String &value, int from_base)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| from_base | int | La base del numero rappresentato dalla stringa |

### Valore restituito

Il valore intero a 8 bit pari al numero rappresentato dalla stringa specificata

## Convert::ToSByte(const String\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la stringa contenente la rappresentazione testuale di un numero nel valore intero senza segno a 8 bit equivalente usando le informazioni di formattazione fornite.

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni sul formato della stringa |

### Valore restituito

Il valore intero a 8 bit pari al numero rappresentato dalla stringa specificata

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, std::nullptr_t) metodo




```cpp
static int8_t System::Convert::ToSByte(const String &value, std::nullptr_t)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la stringa contenente la rappresentazione testuale di un numero nel valore intero a 8 bit equivalente usando le informazioni di formattazione e lo stile numerico forniti.

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell’enumerazione NumberStyles che specifica lo stile consentito della rappresentazione testuale del numero |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni sul formato della stringa |

### Valore restituito

Il valore intero senza segno a 8 bit pari al numero rappresentato dalla stringa specificata

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, std::nullptr_t) metodo




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSByte(Enum) metodo




```cpp
template<typename Enum,typename> static int8_t System::Convert::ToSByte(Enum value)
```

## Convert::ToSByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte il valore boxed specificato in un valore intero a 8 bit equivalente.

```cpp
static int8_t System::Convert::ToSByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Il puntatore condiviso all’oggetto che contiene il valore da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Il formato della stringa da utilizzare se il tipo del valore boxed è [String](../../string/) |

### Valore restituito

Un valore intero a 8 bit equivalente al valore boxed specificato

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