---
title: ToString()
second_title: Referência da API Aspose.Slides para C++
description: Retorna a representação em cadeia de caracteres do intervalo de tempo representado pelo objeto atual.
type: docs
weight: 261
url: /pt/system/timespan/tostring/
---
## TimeSpan::ToString() const método

Retorna a representação em cadeia de caracteres do intervalo de tempo representado pelo objeto atual.

```cpp
String System::TimeSpan::ToString() const
```
## TimeSpan::ToString(const String\&) const método

Converte o valor do objeto atual para uma representação de cadeia de caracteres equivalente, usando o formato especificado.

```cpp
String System::TimeSpan::ToString(const String &format) const
```
## TimeSpan::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const método

Converte o valor do objeto atual para uma representação de cadeia de caracteres equivalente, usando o formato e o provedor de formato especificados.

```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```
## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const método




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```
## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const método




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```
## TimeSpan::ToString(const String\&, std::nullptr_t) const método




```cpp
String System::TimeSpan::ToString(const String &format, std::nullptr_t) const
```
## Ver Também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [TimeSpan](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)