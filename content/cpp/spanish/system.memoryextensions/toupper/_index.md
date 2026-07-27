---
title: ToUpper()
second_title: Aspose.Slides para la API de C++
description: Convierte caracteres a mayúsculas usando la cultura especificada.
type: docs
weight: 469
url: /es/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) función

Convierte caracteres a mayúsculas usando la cultura especificada.

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | El intervalo de caracteres de origen para convertir |
| destination | [Span](../../system/span/)\<char16_t\>\& | El intervalo de destino para almacenar los caracteres convertidos |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | La cultura a usar para la conversión (nullptr para la cultura actual) |

### Valor devuelto

Número de caracteres convertidos, o -1 si el destino es demasiado pequeño

## Ver también

* Typedef [SharedPtr](../../system/sharedptr/)
* Clase [ReadOnlySpan](../../system/readonlyspan/)
* Clase [Span](../../system/span/)
* Clase [CultureInfo](../../system.globalization/cultureinfo/)
* Espacio de nombres [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)