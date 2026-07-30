---
title: Parse()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la stringa specificata che contiene la rappresentazione testuale di un numero nell’intero con segno a 32 bit equivalente.
type: docs
weight: 1
url: /it/system/int32/parse/
---
## Int32::Parse(const String\&) metodo


Converte la stringa specificata che contiene la rappresentazione testuale di un numero nell’intero con segno a 32 bit equivalente.

```cpp
static int32_t System::Int32::Parse(const String &value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |

### Valore di ritorno

L’intero con segno a 32 bit uguale al numero rappresentato dalla stringa specificata.

## Int32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metodo


Converte la stringa specificata che contiene la rappresentazione testuale di un numero nell’intero con segno a 32 bit equivalente usando le informazioni di formattazione fornite.

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formattazione della stringa. |

### Valore di ritorno

L’intero con segno a 32 bit uguale al numero rappresentato dalla stringa specificata.

## Int32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo




```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, std::nullptr_t) metodo




```cpp
static int32_t System::Int32::Parse(const String &value, std::nullptr_t)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodo


Converte la stringa specificata che contiene la rappresentazione testuale di un numero nell’intero con segno a 32 bit equivalente usando le informazioni di formattazione fornite e lo stile numerico.

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../string/)\& | La stringa da convertire. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinazione bitwise dei valori dell’enumerazione NumberStyles che specifica lo stile consentito della rappresentazione testuale di un numero. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntatore a un oggetto che contiene le informazioni di formattazione della stringa. |

### Valore di ritorno

L’intero con segno a 32 bit uguale al numero rappresentato dalla stringa specificata.

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metodo




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metodo 




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&) metodo 




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, std::nullptr_t) metodo 




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, std::nullptr_t)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metodo 




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

## Vedi anche

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Int32](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Classe [ReadOnlySpan](../../readonlyspan/)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)