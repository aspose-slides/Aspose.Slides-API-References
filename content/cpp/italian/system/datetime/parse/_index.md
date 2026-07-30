---
title: Parse()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la rappresentazione stringa specificata di un valore di data e ora nell'oggetto DateTime equivalente.
type: docs
weight: 859
url: /it/system/datetime/parse/
---
## DateTime::Parse(const String\&) metodo


Converte la rappresentazione stringa specificata di un valore di data e ora nell'oggetto [DateTime](../) equivalente.

```cpp
static DateTime System::DateTime::Parse(const String &s)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../string/)\& | La rappresentazione stringa di un valore di data e ora da convertire. |

### Valore restituito

Una nuova istanza della classe [DateTime](../) che rappresenta il valore di data e ora equivalente a quello rappresentato dalla stringa specificata.

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metodo


Converte la rappresentazione stringa specificata di un valore di data e ora nell'oggetto [DateTime](../) equivalente utilizzando le informazioni di formattazione specifiche della cultura.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../string/)\& | La rappresentazione stringa di un valore di data e ora da convertire. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | L'oggetto [IFormatProvider](../../iformatprovider/) che fornisce le informazioni di formattazione specifiche della cultura. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Una combinazione bitwise dei valori di enumerazione che fornisce informazioni aggiuntive su **s**, sugli elementi di stile che possono essere presenti in **s**, o sulla conversione da **s** a un oggetto [DateTime](../). |

### Valore restituito

Una nuova istanza della classe [DateTime](../) che rappresenta il valore di data e ora equivalente a quello rappresentato dalla stringa specificata.

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) metodo




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) metodo




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) metodo




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Vedi anche

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [DateTime](../)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)