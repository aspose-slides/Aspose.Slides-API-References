---
title: ToString()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la rappresentazione stringa dell'intervallo di tempo rappresentato dall'oggetto corrente.
type: docs
weight: 261
url: /it/system/timespan/tostring/
---
## TimeSpan::ToString() const metodo

Restituisce la rappresentazione stringa dell'intervallo di tempo rappresentato dall'oggetto corrente.

```cpp
String System::TimeSpan::ToString() const
```

## TimeSpan::ToString(const String\&) const metodo

Converte il valore dell'oggetto corrente in una rappresentazione stringa equivalente, utilizzando il formato specificato.

```cpp
String System::TimeSpan::ToString(const String &format) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const metodo

Converte il valore dell'oggetto corrente in una rappresentazione stringa equivalente, utilizzando il formato e il provider di formattazione specificati.

```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metodo




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const metodo




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## TimeSpan::ToString(const String\&, std::nullptr_t) const metodo




```cpp
String System::TimeSpan::ToString(const String &format, std::nullptr_t) const
```

## Vedi anche

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [TimeSpan](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Libreria [Aspose.Slides](../../../)