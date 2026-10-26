---
title: TryParse()
second_title: Referencia de API de Aspose.Slides para C++
description: Intenta convertir la cadena especificada a un objeto DateTimeOffset.
type: docs
weight: 729
url: /es/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) method


Intenta convertir la cadena especificada a un objeto [DateTimeOffset](../).

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```


### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) para convertir. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) que es equivalente a la **input**. |

### Return Value

true si la **input** se convierte correctamente, de lo contrario - false.

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method


Intenta convertir la cadena especificada a un objeto [DateTimeOffset](../) usando el proveedor de formato y el estilo de formato especificados.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```


### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) para convertir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Proveedor de formato. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Estilos de formato de fecha y hora. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) que es equivalente a la **input**. |

### Return Value

true si la **input** se convierte correctamente, de lo contrario - false.

## See Also

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)