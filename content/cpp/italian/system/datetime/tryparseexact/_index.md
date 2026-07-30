---
title: TryParseExact()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la rappresentazione in stringa specificata di un valore data e ora nell'oggetto DateTime equivalente utilizzando il formato specificato, le informazioni di formattazione specifiche della cultura e lo stile. Il formato della rappresentazione in stringa deve corrispondere esattamente al formato specificato.
type: docs
weight: 898
url: /it/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) metodo

Converte la rappresentazione stringa specificata di un valore data e ora nell'oggetto [DateTime](../) equivalente utilizzando il formato specificato, le informazioni di formattazione specifiche della cultura e lo stile. Il formato della rappresentazione stringa deve corrispondere esattamente al formato specificato.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../string/)\& | La rappresentazione stringa di un valore data e ora da convertire. |
| format | const [String](../../string/)\& | Il formato stringa. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | L'oggetto [IFormatProvider](../../iformatprovider/) che fornisce le informazioni di formattazione specifiche della cultura. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Una combinazione bitwise dei valori di enumerazione che fornisce informazioni aggiuntive su **s**, sugli elementi di stile che possono essere presenti in **s**, o sulla conversione da **s** a un oggetto [DateTime](../). |
| result | [DateTime](../)\& | L'argomento di output che, se la conversione ha successo, contiene il risultato della conversione. |

### Valore di ritorno

True se la conversione riesce, altrimenti - false.

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metodo




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metodo




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) metodo




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) metodo

Converte la rappresentazione stringa specificata di un valore data e ora nell'oggetto [DateTime](../) equivalente utilizzando i formati specificati, le informazioni di formattazione specifiche della cultura e lo stile. Il formato della rappresentazione stringa deve corrispondere esattamente a uno o più dei formati specificati.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../string/)\& | La rappresentazione stringa di un valore data e ora da convertire. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | L'array di formati stringa. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | L'oggetto [IFormatProvider](../../iformatprovider/) che fornisce le informazioni di formattazione specifiche della cultura. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Una combinazione bitwise dei valori di enumerazione che fornisce informazioni aggiuntive su **s**, sugli elementi di stile che possono essere presenti in **s**, o sulla conversione da **s** a un oggetto [DateTime](../). |
| result | [DateTime](../)\& | L'argomento di output che, se la conversione ha successo, contiene il risultato della conversione. |

### Valore di ritorno

True se la conversione riesce, altrimenti - false.

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metodo




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metodo




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) metodo




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Vedi anche

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTime](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)