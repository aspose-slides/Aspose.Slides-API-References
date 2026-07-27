---
title: ParseExact()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte la cadena especificada en un objeto DateTimeOffset utilizando el formato especificado, el proveedor de formato y el estilo de formato.
type: docs
weight: 716
url: /es/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String&, const String&, const SharedPtr<IFormatProvider>&, Globalization::DateTimeStyles) método

Convierte la cadena especificada a un objeto [DateTimeOffset](../) usando el formato especificado, el proveedor de formato y el estilo de formato.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../string/)& | [String](../../string/) a convertir. |
| format | const [String](../../string/)& | Cadena de formato. |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | Proveedor de formato. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Estilos de formato de fecha y hora. |

### Valor devuelto

[DateTimeOffset](../) que es equivalente al **input**.

## DateTimeOffset::ParseExact(const String&, const ArrayPtr<String>&, const SharedPtr<IFormatProvider>&, Globalization::DateTimeStyles) método

Convierte la cadena especificada a un objeto [DateTimeOffset](../) usando los formatos especificados, el proveedor de formato y el estilo de formato.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../string/)& | [String](../../string/) a convertir. |
| formats | const [ArrayPtr](../../arrayptr/)<[String](../../string/)>& | [Array](../../array/) de cadenas de formato. |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | Proveedor de formato. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Estilos de formato de fecha y hora. |

### Valor devuelto

[DateTimeOffset](../) que es equivalente al **input**.

## Véase también

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Clase [DateTimeOffset](../)
* Clase [String](../../string/)
* Clase [IFormatProvider](../../iformatprovider/)
* Espacio de nombres [System](../../)
* Library [Aspose.Slides](../../../)