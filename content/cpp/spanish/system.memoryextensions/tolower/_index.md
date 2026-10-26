---
title: ToLower()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte caracteres a minúsculas usando la cultura especificada.
type: docs
weight: 443
url: /es/system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) función

Convierte caracteres a minúsculas usando la cultura especificada.

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | El span de caracteres de origen a convertir |
| destination | [Span](../../system/span/)\<char16_t\>\& | El span de destino donde almacenar los caracteres convertidos |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | La cultura a usar para la conversión (nullptr para la cultura actual) |

### Valor devuelto

Número de caracteres convertidos, o -1 si el destino es demasiado pequeño

## Ver también

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Class [CultureInfo](../../system.globalization/cultureinfo/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)