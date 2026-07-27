---
title: TryParse()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte la cadena especificada que contiene la representación textual de un número al valor de punto flotante de precisión simple equivalente.
type: docs
weight: 14
url: /es/system/single/tryparse/
---
## Single::TryParse(const String\&, float\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor de punto flotante de precisión simple equivalente.

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| result | **float**\& | La referencia a una variable de punto flotante de precisión simple donde se coloca el resultado de la conversión. |

### Valor devuelto

True si la conversión tuvo éxito, de lo contrario - false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, float\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor de punto flotante de precisión simple equivalente utilizando la información de formato y el estilo de número proporcionados.

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de los valores del enumerado NumberStyles que especifica el estilo permitido de la representación textual de un número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena. |
| result | **float**\& | La referencia a una variable de punto flotante de precisión simple donde se coloca el resultado de la conversión. |

### Valor devuelto

True si la conversión tuvo éxito, de lo contrario - false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, float\&) método

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, float\&) método

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, float\&) método

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
```

## Véase también

* Enumeración [NumberStyles](../../../system.globalization/numberstyles/)
* Definición de tipo [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Estructura [Single](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)