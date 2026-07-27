---
title: TryParse()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte la cadena especificada que contiene la representación en forma de cadena de un número al valor Decimal equivalente.
type: docs
weight: 482
url: /es/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) método

Convierte la cadena especificada que contiene la representación en forma de cadena de un número al valor [Decimal](../) equivalente.

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| result | [Decimal](../)\& | La referencia a una variable [Decimal](../) donde se coloca el resultado de la conversión |

### Valor devuelto

True si la conversión tuvo éxito, de lo contrario - false

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) método

Convierte la cadena especificada que contiene la representación en forma de cadena de un número al valor [Decimal](../) equivalente utilizando la información de formato y el estilo de número proporcionados.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | const [String](../../string/)\& | La cadena a convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Una combinación bit a bit de los valores del enumerado NumberStyles que especifica el estilo permitido de la representación en forma de cadena de un número |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un puntero a un objeto que contiene la información de formato de cadena |
| result | [Decimal](../)\& | Un argumento de salida; contiene el resultado de la conversión |

### Valor devuelto

True si la conversión tuvo éxito, de lo contrario - false

## Ver también

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [Decimal](../)
* Clase [IFormatProvider](../../iformatprovider/)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)