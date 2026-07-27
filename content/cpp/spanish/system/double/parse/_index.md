---
title: Parse()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte la cadena especificada que contiene la representación textual de un número al valor de punto flotante de doble precisión equivalente.
type: docs
weight: 1
url: /es/system/double/parse/
---
## Double::Parse(const String\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor de punto flotante de doble precisión equivalente.

```cpp
static double System::Double::Parse(const String &value)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |

### Valor devuelto

El valor de punto flotante de doble precisión igual al número representado por la cadena especificada.

## Double::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor de punto flotante de doble precisión equivalente usando la información de formato proporcionada.

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de la cadena. |

### Valor devuelto

El valor de punto flotante de doble precisión igual al número representado por la cadena especificada.

## Double::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, std::nullptr_t) método




```cpp
static double System::Double::Parse(const String &value, std::nullptr_t)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) método

Convierte la cadena especificada que contiene la representación textual de un número al valor de punto flotante de doble precisión equivalente usando la información de formato y el estilo numérico proporcionados.

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de los valores de la enumeración NumberStyles que especifica el estilo permitido de la representación textual de un número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de la cadena. |

### Valor devuelto

El valor de punto flotante de doble precisión igual al número representado por la cadena especificada.

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) método




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) método




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) método




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Ver también

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)