---
title: ToUInt16()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte il valore booleano specificato in un corrispondente intero senza segno a 16 bit.
type: docs
weight: 144
url: /it/system/convert/touint16/
---
## Convert::ToUInt16(bool) metodo


Converte il valore booleano specificato in un corrispondente intero senza segno a 16 bit.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(bool value)
```

## Convert::ToUInt16(uint8_t) metodo


Converte l'intero senza segno a 8 bit specificato in un corrispondente intero senza segno a 16 bit.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(uint8_t value)
```

## Convert::ToUInt16(int8_t) metodo


Converte l'intero con segno a 8 bit specificato in un corrispondente intero senza segno a 16 bit.

```cpp
static uint16_t System::Convert::ToUInt16(int8_t value)
```

## Convert::ToUInt16(uint16_t) metodo


Restituisce l'intero senza segno a 16 bit specificato.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(uint16_t value)
```

## Convert::ToUInt16(int16_t) metodo


Converte l'intero con segno a 16 bit specificato in un corrispondente intero senza segno a 16 bit.

```cpp
static uint16_t System::Convert::ToUInt16(int16_t value)
```

## Convert::ToUInt16(uint32_t) metodo


Converte l'intero senza segno a 32 bit specificato in un corrispondente intero senza segno a 16 bit.

```cpp
static uint16_t System::Convert::ToUInt16(uint32_t value)
```

## Convert::ToUInt16(int32_t) metodo


Converte l'intero con segno a 32 bit specificato in un corrispondente intero senza segno a 16 bit.

```cpp
static uint16_t System::Convert::ToUInt16(int32_t value)
```

## Convert::ToUInt16(uint64_t) metodo


Converte l'intero senza segno a 64 bit specificato in un corrispondente intero senza segno a 16 bit.

```cpp
static uint16_t System::Convert::ToUInt16(uint64_t value)
```

## Convert::ToUInt16(int64_t) metodo


Converte l'intero con segno a 64 bit specificato in un corrispondente intero senza segno a 16 bit.

```cpp
static uint16_t System::Convert::ToUInt16(int64_t value)
```

## Convert::ToUInt16(float) metodo


Converte il numero float specificato in un corrispondente intero senza segno a 16 bit.

```cpp
static uint16_t System::Convert::ToUInt16(float value)
```

## Convert::ToUInt16(double) metodo


Converte il numero double specificato in un corrispondente intero senza segno a 16 bit.

```cpp
static uint16_t System::Convert::ToUInt16(double value)
```

## Convert::ToUInt16(const Decimal\&) metodo


Converte il numero decimale specificato in un corrispondente intero senza segno a 16 bit.

```cpp
static uint16_t System::Convert::ToUInt16(const Decimal &value)
```

## Convert::ToUInt16(char_t) metodo


Converte il carattere Unicode specificato in un corrispondente intero senza segno a 16 bit.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(char_t value)
```

## Convert::ToUInt16(DateTime) metodo


La conversione non è supportata. Genera sempre InvalidCastException.

```cpp
static uint16_t System::Convert::ToUInt16(DateTime value)
```

## Convert::ToUInt16(std::nullptr_t) metodo


Converte la stringa null specificata nel valore intero senza segno a 16 bit equivalente.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(std::nullptr_t)
```


### Valore di ritorno

Zero.

## Convert::ToUInt16(const char_t *) metodo


Converte la c-string contenente la rappresentazione testuale di un numero nel valore intero senza segno a 16 bit equivalente.

```cpp
static uint16_t System::Convert::ToUInt16(const char_t *value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const char_t * | La c-string da convertire |

### Valore di ritorno

Il valore intero senza segno a 16 bit uguale al numero rappresentato dalla c-string specificata

## Convert::ToUInt16(const String\&) metodo


Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 16 bit equivalente.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |

### Valore di ritorno

Il valore intero senza segno a 16 bit uguale al numero rappresentato dalla stringa specificata

## Convert::ToUInt16(const String\&, int) metodo


Converte la stringa specificata contenente la rappresentazione testuale di un numero nella base specificata nel valore intero senza segno a 16 bit equivalente.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, int from_base)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| from_base | int | La base del numero rappresentato dalla stringa |

### Valore di ritorno

Il valore intero senza segno a 16 bit uguale al numero rappresentato dalla stringa specificata

## Convert::ToUInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) metodo


Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 16 bit equivalente utilizzando le informazioni di formattazione fornite.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formattazione della stringa |

### Valore di ritorno

Il valore intero senza segno a 16 bit uguale al numero rappresentato dalla stringa specificata

## Convert::ToUInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt16(const String\&, std::nullptr_t) metodo




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, std::nullptr_t)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodo


Converte la stringa specificata contenente la rappresentazione testuale di un numero nel valore intero senza segno a 16 bit equivalente utilizzando le informazioni di formattazione fornite e lo stile numerico.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell'enumerazione NumberStyles che specifica lo stile consentito della rappresentazione testuale del numero |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formattazione della stringa |

### Valore di ritorno

Il valore intero senza segno a 16 bit uguale al numero rappresentato dalla stringa specificata

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) metodo




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt16(Enum) metodo




```cpp
template<typename Enum,typename> static uint16_t System::Convert::ToUInt16(Enum value)
```

## Convert::ToUInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metodo


Converte il valore boxed specificato in un valore intero senza segno a 16 bit equivalente.

```cpp
static uint16_t System::Convert::ToUInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Il puntatore condiviso all'oggetto che incapsula il valore da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Il formato della stringa da utilizzare se il tipo del valore boxed è [String](../../string/) |

### Valore di ritorno

Un valore intero senza segno a 16 bit equivalente al valore boxed specificato

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