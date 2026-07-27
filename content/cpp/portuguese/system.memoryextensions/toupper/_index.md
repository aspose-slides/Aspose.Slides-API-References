---
title: ToUpper()
second_title: Aspose.Slides para C++ Referência da API
description: Converte caracteres para maiúsculas usando a cultura especificada.
type: docs
weight: 469
url: /pt/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) function

Converte caracteres para maiúsculas usando a cultura especificada.

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | O intervalo de caracteres de origem a ser convertido |
| destination | [Span](../../system/span/)\<char16_t\>\& | O intervalo de destino para armazenar os caracteres convertidos |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | A cultura a ser usada na conversão (nullptr para a cultura atual) |

### Valor de Retorno

Número de caracteres convertidos, ou -1 se o destino for pequeno demais

## Ver Também

* Typedef [SharedPtr](../../system/sharedptr/)
* Classe [ReadOnlySpan](../../system/readonlyspan/)
* Classe [Span](../../system/span/)
* Classe [CultureInfo](../../system.globalization/cultureinfo/)
* Namespace [System::MemoryExtensions](../)
* Biblioteca [Aspose.Slides](../../)