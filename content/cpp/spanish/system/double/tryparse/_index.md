---
title: TryParse()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte la cadena especificada que contiene la representación textual de un número al valor de punto flotante de doble precisión equivalente.
type: docs
weight: 14
url: /es/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor de punto flotante de doble precisión equivalente.

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| result | **double**\& | La referencia a una variable de punto flotante de doble precisión donde se coloca el resultado de la conversión. |

### Valor devuelto

True si la conversión tuvo éxito, de lo contrario - false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) método


Convierte la cadena especificada que contiene la representación textual de un número al valor de punto flotante de doble precisión equivalente utilizando la información de formato y el estilo de número proporcionados.

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de valores del enum NumberStyles que especifica el estilo permitido de la representación textual de un número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena. |
| result | **double**\& | La referencia a una variable de punto flotante de doble precisión donde se coloca el resultado de la conversión. |

### Valor devuelto

True si la conversión tuvo éxito, de lo contrario - false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) método




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) método




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) método




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## Ver también

* Enumeración [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Estructura [Double](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)