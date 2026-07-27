---
title: ToLower()
second_title: Referência da API Aspose.Slides para C++
description: Converte caracteres para minúsculas usando a cultura especificada.
type: docs
weight: 443
url: /pt/system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) função


Converte caracteres para minúsculas usando a cultura especificada.

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The source character span to convert |
| destination | [Span](../../system/span/)\<char16_t\>\& | The destination span to store converted characters |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | The culture to use for conversion (nullptr for current culture) |

### Valor de Retorno

Number of characters converted, or -1 if destination is too small

## Veja Também

* Typedef [SharedPtr](../../system/sharedptr/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Classe [CultureInfo](../../system.globalization/cultureinfo/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)