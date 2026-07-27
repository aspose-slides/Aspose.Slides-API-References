---
title: TryParse()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte una cadena al objeto TimeSpan equivalente y devuelve el resultado de la conversión.
type: docs
weight: 560
url: /es/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) método


Convierte una cadena al objeto [TimeSpan](../) equivalente y devuelve el resultado de la conversión.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../string/)\& | Cadena de entrada. |
| result | [TimeSpan](../)\& | Intervalo de tiempo que corresponde a la cadena. |

### Valor de retorno

True si la cadena se convirtió correctamente; de lo contrario, false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) método


Convierte una cadena al objeto [TimeSpan](../) equivalente usando el proveedor de formato especificado y devuelve el resultado de la conversión.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../string/)\& | Cadena de entrada. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Proveedor de formato que suministra información de formato específica de la cultura. |
| result | [TimeSpan](../)\& | Intervalo de tiempo que corresponde a la cadena. |

### Valor de retorno

True si la cadena se convirtió correctamente; de lo contrario, false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) método




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) método




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) método




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [TimeSpan](../)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)