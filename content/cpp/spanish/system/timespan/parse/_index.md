---
title: Parse()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte cadena a un objeto TimeSpan equivalente.
type: docs
weight: 534
url: /es/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) método

Convierte cadena a un objeto [TimeSpan](../) equivalente.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../string/)\& | Cadena de entrada. |

### Valor devuelto

Intervalo de tiempo que corresponde a la cadena.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) método

Convierte cadena a un objeto [TimeSpan](../) equivalente utilizando el proveedor de formato especificado.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../string/)\& | Cadena de entrada. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Proveedor de formato que suministra información de formato específica de la cultura. |

### Valor devuelto

Intervalo de tiempo que corresponde a la cadena.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) método




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) método




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [TimeSpan](../)
* Clase [String](../../string/)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)