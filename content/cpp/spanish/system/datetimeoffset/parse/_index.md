---
title: Parse()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte la cadena especificada a un equivalente de DateTimeOffset.
type: docs
weight: 703
url: /es/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) método

Convierte la cadena especificada a un equivalente de [DateTimeOffset](../).

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) para convertir. |

### Valor de retorno

[DateTimeOffset](../) que es equivalente al **input**.

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) método

Convierte la cadena especificada a un objeto [DateTimeOffset](../) utilizando el proveedor de formato y el estilo de formato especificados.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) para convertir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Proveedor de formato. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Estilos de formato de fecha y hora. |

### Valor de retorno

[DateTimeOffset](../) que es equivalente al **input**.

## Ver también

* Enumeración [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Clase [DateTimeOffset](../)
* Clase [String](../../string/)
* Clase [IFormatProvider](../../iformatprovider/)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)