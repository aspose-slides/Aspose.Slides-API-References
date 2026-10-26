---
title: ToDateTime()
second_title: Riferimento API Aspose.Slides per C++
description: La conversione non è supportata. Lancia sempre InvalidCastException.
type: docs
weight: 248
url: /it/system/convert/todatetime/
---
## Convert::ToDateTime(bool) metodo


La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(bool value)
```

## Convert::ToDateTime(uint8_t) metodo


La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint8_t value)
```

## Convert::ToDateTime(int8_t) metodo


La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int8_t value)
```

## Convert::ToDateTime(uint16_t) metodo


La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint16_t value)
```

## Convert::ToDateTime(int16_t) metodo


La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int16_t value)
```

## Convert::ToDateTime(uint32_t) metodo


La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint32_t value)
```

## Convert::ToDateTime(int32_t) metodo


La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int32_t value)
```

## Convert::ToDateTime(uint64_t) metodo


La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint64_t value)
```

## Convert::ToDateTime(int64_t) metodo


La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int64_t value)
```

## Convert::ToDateTime(float) metodo


La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(float value)
```

## Convert::ToDateTime(double) metodo


La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(double value)
```

## Convert::ToDateTime(const Decimal\&) metodo


La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(const Decimal &value)
```

## Convert::ToDateTime(char_t) metodo


La conversione non è supportata. Lancia sempre InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(char_t value)
```

## Convert::ToDateTime(DateTime) metodo


Restituisce la data e l'ora specificate.

```cpp
static constexpr DateTime System::Convert::ToDateTime(DateTime value)
```

## Convert::ToDateTime(const String\&) metodo


Converte la stringa specificata in un'istanza della classe [DateTime](../../datetime/).

```cpp
static DateTime System::Convert::ToDateTime(const String &value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |

### Valore restituito

Un'istanza della classe [DateTime](../../datetime/) che rappresenta le informazioni di data e ora contenute nella stringa specificata

## Convert::ToDateTime(const String\&, const SharedPtr\<IFormatProvider\>\&) metodo


Converte la stringa specificata in un'istanza della classe [DateTime](../../datetime/) utilizzando le informazioni di formattazione fornite.

```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<IFormatProvider> &fp)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni sul formato della stringa |

### Valore restituito

Un'istanza della classe [DateTime](../../datetime/) che rappresenta le informazioni di data e ora contenute nella stringa specificata

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) metodo




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## Convert::ToDateTime(const String\&, std::nullptr_t) metodo




```cpp
static DateTime System::Convert::ToDateTime(const String &value, std::nullptr_t)
```

## Convert::ToDateTime(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metodo


Converte il valore boxed specificato in un valore [DateTime](../../datetime/) equivalente.

```cpp
static DateTime System::Convert::ToDateTime(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Il puntatore condiviso all'oggetto che contiene il valore da convertire |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Il formato della stringa da utilizzare se il tipo del valore boxed è [String](../../string/) |

### Valore restituito

Un valore [DateTime](../../datetime/) equivalente al valore boxed specificato

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../../datetime/)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)