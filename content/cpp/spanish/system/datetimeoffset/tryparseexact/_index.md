---
title: TryParseExact()
second_title: Referencia de API de Aspose.Slides para C++
description: Intenta convertir la cadena especificada en un objeto DateTimeOffset usando los formatos especificados, el proveedor de formato y el estilo de formato.
type: docs
weight: 742
url: /es/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) método

Intenta convertir la cadena especificada en un objeto [DateTimeOffset](../) usando los formatos especificados, el proveedor de formato y el estilo de formato.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) para convertir. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Matriz de cadenas de formato. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Proveedor de formato. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Estilos de formato de fecha y hora. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) que es equivalente al **input**. |

### Valor devuelto

true si el **input** se convierte correctamente, de lo contrario - false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) método

Intenta convertir la cadena especificada en un objeto [DateTimeOffset](../) usando el formato especificado, el proveedor de formato y el estilo de formato.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) para convertir. |
| format | const [String](../../string/)\& | Cadena de formato. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Proveedor de formato. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Estilos de formato de fecha y hora. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) que es equivalente al **input**. |

### Valor devuelto

true si el **input** se convierte correctamente, de lo contrario - false.

## Ver también

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Clase [String](../../string/)
* Clase [IFormatProvider](../../iformatprovider/)
* Clase [DateTimeOffset](../)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)