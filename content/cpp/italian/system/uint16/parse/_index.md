---
title: Parse()
second_title: Riferimento API Aspose.Slides per C++
description: Converte la stringa specificata contenente la rappresentazione testuale di un numero nell'intero senza segno a 16-bit equivalente.
type: docs
weight: 1
url: /it/system/uint16/parse/
---
## UInt16::Parse(const String\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nell'intero senza segno a 16 bit equivalente.

```cpp
static uint16_t System::UInt16::Parse(const String &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |

### Valore di ritorno

L'intero senza segno a 16 bit uguale al numero rappresentato dalla stringa specificata.

## UInt16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nell'intero senza segno a 16 bit equivalente utilizzando le informazioni di formattazione fornite.

```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formattazione della stringa. |

### Valore di ritorno

L'intero senza segno a 16 bit uguale al numero rappresentato dalla stringa specificata.

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, std::nullptr_t) metodo




```cpp
static uint16_t System::UInt16::Parse(const String &value, std::nullptr_t)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la stringa specificata contenente la rappresentazione testuale di un numero nell'intero senza segno a 16 bit equivalente utilizzando le informazioni di formattazione fornite e lo stile numerico.

```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell'enumerazione NumberStyles che specifica lo stile consentito della rappresentazione testuale di un numero. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formattazione della stringa. |

### Valore di ritorno

L'intero senza segno a 16 bit uguale al numero rappresentato dalla stringa specificata.

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metodo




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Vedi anche

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)