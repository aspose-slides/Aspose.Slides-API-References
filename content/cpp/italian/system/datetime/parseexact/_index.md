---
title: ParseExact()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la rappresentazione stringa specificata di un valore di data e ora nell'oggetto DateTime equivalente usando il formato specificato e le informazioni di formato specifiche per la cultura. Il formato della rappresentazione stringa deve corrispondere esattamente al formato specificato. Genera un'eccezione se la conversione fallisce.
type: docs
weight: 872
url: /it/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metodo

Converte la rappresentazione stringa specificata di un valore di data e ora nell'oggetto [DateTime](../) equivalente utilizzando il formato specificato e le informazioni di formato specifiche per la cultura. Il formato della rappresentazione stringa deve corrispondere esattamente al formato specificato. Genera un'eccezione se la conversione non riesce.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../string/)\& | La rappresentazione stringa di un valore di data e ora da convertire. |
| format | const [String](../../string/)\& | Il formato stringa. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | L'oggetto [IFormatProvider](../../iformatprovider/) che fornisce informazioni di formato specifiche per la cultura. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Una combinazione bitwise dei valori dell'enumerazione che fornisce informazioni aggiuntive su **s**, sugli elementi di stile che possono essere presenti in **s**, o sulla conversione da **s** a un oggetto [DateTime](../). |

### Valore di ritorno

Una nuova istanza della classe [DateTime](../) che rappresenta il valore di data e ora equivalente a quello rappresentato dalla stringa specificata.

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metodo




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metodo




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) metodo




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metodo

Converte la rappresentazione stringa specificata di un valore di data e ora nell'oggetto [DateTime](../) equivalente utilizzando i formati specificati, le informazioni di formato specifiche per la cultura e lo stile. Il formato della rappresentazione stringa deve corrispondere esattamente a uno o più dei formati specificati. Genera un'eccezione se la conversione non riesce.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../string/)\& | La rappresentazione stringa di un valore di data e ora da convertire. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | L'array dei formati stringa. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | L'oggetto [IFormatProvider](../../iformatprovider/) che fornisce informazioni di formato specifiche per la cultura. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Una combinazione bitwise dei valori dell'enumerazione che fornisce informazioni aggiuntive su **s**, sugli elementi di stile che possono essere presenti in **s**, o sulla conversione da **s** a un oggetto [DateTime](../). |

### Valore di ritorno

Una nuova istanza della classe [DateTime](../) che rappresenta il valore di data e ora equivalente a quello rappresentato dalla stringa specificata.

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metodo




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metodo




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) metodo




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## Vedi anche

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)