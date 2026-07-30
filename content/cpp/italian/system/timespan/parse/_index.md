---
title: Parse()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la stringa in un oggetto TimeSpan equivalente.
type: docs
weight: 534
url: /it/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) metodo

Converte la stringa in un oggetto [TimeSpan](../) equivalente.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../string/)\& | Stringa di input. |

### Valore di ritorno

Intervallo di tempo corrispondente alla stringa.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metodo

Converte la stringa in un oggetto [TimeSpan](../) equivalente utilizzando il provider di formato specificato.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../string/)\& | Stringa di input. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provider di formato che fornisce informazioni di formattazione specifiche per la cultura. |

### Valore di ritorno

Intervallo di tempo corrispondente alla stringa.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metodo




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) metodo




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) metodo




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Class [TimeSpan](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)