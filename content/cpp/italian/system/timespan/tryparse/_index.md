---
title: TryParse()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte stringa in un oggetto TimeSpan equivalente e restituisce il risultato della conversione.
type: docs
weight: 560
url: /it/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) metodo


Converte la stringa in un oggetto [TimeSpan](../) equivalente e restituisce il risultato della conversione.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../string/)\& | Stringa di input. |
| result | [TimeSpan](../)\& | Intervallo di tempo corrispondente alla stringa. |

### Valore di ritorno

True se la stringa è stata convertita con successo; altrimenti, false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) metodo


Converte la stringa in un oggetto [TimeSpan](../) equivalente usando il provider di formato specificato e restituisce il risultato della conversione.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../string/)\& | Stringa di input. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provider di formato che fornisce informazioni di formattazione specifiche per la cultura. |
| result | [TimeSpan](../)\& | Intervallo di tempo corrispondente alla stringa. |

### Valore di ritorno

True se la stringa è stata convertita con successo; altrimenti, false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) metodo




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) metodo




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) metodo




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [TimeSpan](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)