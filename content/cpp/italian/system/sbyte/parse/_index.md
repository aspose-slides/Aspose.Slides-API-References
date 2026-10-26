---
title: Parse()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la stringa specificata contenente la rappresentazione testuale di un numero nell'intero con segno a 8 bit equivalente.
type: docs
weight: 1
url: /it/system/sbyte/parse/
---
## SByte::Parse(const String\&) metodo


Converte la stringa specificata contenente la rappresentazione testuale di un numero nell’intero con segno a 8 bit equivalente.

```cpp
static int8_t System::SByte::Parse(const String &value)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |

### Valore di ritorno

L’intero con segno a 8 bit uguale al numero rappresentato dalla stringa specificata.

## SByte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metodo


Converte la stringa specificata contenente la rappresentazione testuale di un numero nell’intero con segno a 8 bit equivalente usando le informazioni di formattazione fornite.

```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formattazione della stringa. |

### Valore di ritorno

L’intero con segno a 8 bit uguale al numero rappresentato dalla stringa specificata.

## SByte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, std::nullptr_t) metodo




```cpp
static int8_t System::SByte::Parse(const String &value, std::nullptr_t)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodo


Converte la stringa specificata contenente la rappresentazione testuale di un numero nell’intero con segno a 8 bit equivalente usando le informazioni di formattazione fornite e lo stile del numero.

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell’enumerazione NumberStyles che specifica lo stile consentito della rappresentazione testuale di un numero. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formattazione della stringa. |

### Valore di ritorno

L’intero con segno a 8 bit uguale al numero rappresentato dalla stringa specificata.

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo 




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metodo 




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Vedi anche

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* classe [String](../../string/)
* classe [IFormatProvider](../../iformatprovider/)
* classe [CultureInfo](../../../system.globalization/cultureinfo/)
* classe [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* namespace [System](../../)
* Library [Aspose.Slides](../../../)