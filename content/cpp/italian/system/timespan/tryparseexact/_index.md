---
title: TryParseExact()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la stringa in un oggetto TimeSpan equivalente utilizzando i formati specificati e il provider di formattazione, e restituisce il risultato della conversione.
type: docs
weight: 573
url: /it/system/timespan/tryparseexact/
---
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) method


Converte la stringa in un oggetto [TimeSpan](../) equivalente utilizzando i formati specificati e il provider di formattazione, e restituisce il risultato della conversione.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../string/)\& | Stringa di input. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) di stringhe di formato. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provider di formato che fornisce informazioni di formattazione specifiche della cultura. |
| result | [TimeSpan](../)\& | Intervallo di tempo corrispondente alla stringa. |

### Valore restituito

True se la stringa è stata convertita correttamente; altrimenti, false.

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method


Converte la stringa in un oggetto [TimeSpan](../) equivalente utilizzando il formato specificato, il provider di formattazione e gli stili, e restituisce il risultato della conversione.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../string/)\& | Stringa di input. |
| format | const [String](../../string/)\& | Stringa di formato standard o personalizzata. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provider di formato che fornisce informazioni di formattazione specifiche della cultura. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Definisce gli elementi che possono essere presenti nella stringa di input. |
| result | [TimeSpan](../)\& | Intervallo di tempo corrispondente alla stringa. |

### Valore restituito

True se la stringa è stata convertita correttamente; altrimenti, false.

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method


Converte la stringa in un oggetto [TimeSpan](../) equivalente utilizzando i formati specificati, il provider di formattazione e gli stili, e restituisce il risultato della conversione.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../string/)\& | Stringa di input. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) di stringhe di formato. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provider di formato che fornisce informazioni di formattazione specifiche della cultura. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Definisce gli elementi che possono essere presenti nella stringa di input. |
| result | [TimeSpan](../)\& | Intervallo di tempo corrispondente alla stringa. |

### Valore restituito

True se la stringa è stata convertita correttamente; altrimenti, false.

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) method


Converte la stringa in un oggetto [TimeSpan](../) equivalente utilizzando il formato specificato e il provider di formattazione, e restituisce il risultato della conversione.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | const [String](../../string/)\& | Stringa di input. |
| format | const [String](../../string/)\& | Stringa di formato standard o personalizzata. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Provider di formato che fornisce informazioni di formattazione specifiche della cultura. |
| result | [TimeSpan](../)\& | Intervallo di tempo corrispondente alla stringa. |

### Valore restituito

True se la stringa è stata convertita correttamente; altrimenti, false.

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, TimeSpan\&) method




```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, TimeSpan &result)
```

## Vedi anche

* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [TimeSpan](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)