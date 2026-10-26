---
title: TryParse()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la rappresentazione stringa specificata di un valore data e ora nell'oggetto DateTime equivalente.
type: docs
weight: 885
url: /it/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) metodo


Converte la rappresentazione stringa specificata di un valore data e ora nell'oggetto [DateTime](../) equivalente.

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../string/)\& | La rappresentazione stringa di un valore data e ora da convertire. |
| result | [DateTime](../)\& | L'argomento di output che, se la conversione riesce, contiene il risultato della conversione. |

### Valore restituito

True se la conversione riesce, altrimenti - false.

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) metodo


Converte la rappresentazione stringa specificata di un valore data e ora nell'oggetto [DateTime](../) equivalente utilizzando le informazioni di formato specifiche della cultura e lo stile specificati.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| s | const [String](../../string/)\& | La rappresentazione stringa di un valore data e ora da convertire. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | L'oggetto [IFormatProvider](../../iformatprovider/) che fornisce informazioni di formato specifiche della cultura. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Una combinazione bitwise dei valori di enumerazione che fornisce informazioni aggiuntive su **s**, sugli elementi di stile che possono essere presenti in **s**, o sulla conversione da **s** a un oggetto [DateTime](../). |
| result | [DateTime](../)\& | L'argomento di output che, se la conversione riesce, contiene il risultato della conversione. |

### Valore restituito

True se la conversione riesce, altrimenti - false.

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metodo




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) metodo




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) metodo




```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Vedi anche

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [DateTime](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Spazio dei nomi [System](../../)
* Library [Aspose.Slides](../../../)