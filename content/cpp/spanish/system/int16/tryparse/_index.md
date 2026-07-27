---
title: TryParse()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero con signo de 16 bits equivalente.
type: docs
weight: 14
url: /es/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) método

Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero con signo de 16 bits equivalente.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| result | **int16_t**\& | La referencia a una variable de entero con signo de 16 bits donde se coloca el resultado de la conversión. |

### Valor de retorno

True si la conversión se realizó correctamente, de lo contrario - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) método

Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero con signo de 16 bits equivalente utilizando la información de formato y el estilo de número proporcionados.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de valores del enum NumberStyles que especifica el estilo permitido de la representación en forma de cadena de un número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena. |
| result | **int16_t**\& | La referencia a una variable de entero con signo de 16 bits donde se coloca el resultado de la conversión. |

### Valor de retorno

True si la conversión se realizó correctamente, de lo contrario - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) método




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) método




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) método




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## Ver también

* Enumeración [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [Int16](../)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)