---
title: TryParse()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero sin signo de 64-bit equivalente.
type: docs
weight: 14
url: /es/system/uint64/tryparse/
---
## UInt64::TryParse(const String\&, uint64_t\&) método


Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero sin signo de 64 bits equivalente.

```cpp
static bool System::UInt64::TryParse(const String &value, uint64_t &result)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| result | **uint64_t**\& | La referencia a una variable de entero sin signo de 64 bits donde se coloca el resultado de la conversión. |

### Valor de retorno

True si la conversión tuvo éxito, de lo contrario - false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint64_t\&) método


Convierte la cadena especificada que contiene la representación en forma de cadena de un número al entero sin signo de 64 bits equivalente utilizando la información de formato y el estilo numérico proporcionados.

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint64_t &result)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de valores del enum NumberStyles que especifica el estilo permitido de la representación en forma de cadena de un número. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena. |
| result | **uint64_t**\& | La referencia a una variable de entero sin signo de 64 bits donde se coloca el resultado de la conversión. |

### Valor de retorno

True si la conversión tuvo éxito, de lo contrario - false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint64_t\&) método




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint64_t\&) método




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint64_t\&) método




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint64_t &result)
```

## Ver también

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [CultureInfo](../../../system.globalization/cultureinfo/)
* Clase [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt64](../)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)