---
title: CompressionLevel
second_title: Referência da API Aspose.Slides para C++
description: Especifica os níveis de compressão ZIP para arquivos OpenXML. Níveis mais altos oferecem melhor compressão ao custo de processamento mais lento.
type: docs
weight: 846
url: /pt/aspose.slides.export/compressionlevel/
---
## CompressionLevel enum

Especifica os níveis de compressão ZIP para arquivos OpenXML. Níveis mais altos oferecem melhor compressão ao custo de processamento mais lento.

```cpp
enum class CompressionLevel
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| None | 0 | Nenhuma compressão é aplicada. Os arquivos são armazenados como estão. |
| Level1 | 1 | Compressão mais rápida com a menor taxa de compressão. |
| Level2 | 2 | Compressão mais rápida com taxa de compressão ligeiramente melhor que [CompressionLevel::Level1](./). |
| Level3 | 3 | Fornece melhor compressão que [CompressionLevel::Level2](./) com impacto moderado de desempenho. |
| Level4 | 4 | Fornece melhor compressão que [CompressionLevel::Level3](./). |
| Level5 | 5 | Fornece compressão aprimorada em relação a [CompressionLevel::Level4](./) com tempo de processamento adicional. |
| Level6 | 6 | Compressão padrão, oferecendo um bom equilíbrio entre velocidade de compressão e tamanho do arquivo. O nível de compressão padrão. |
| Level7 | 7 | Fornece compressão maior que [CompressionLevel::Level6](./) com processamento mais lento. |
| Level8 | 8 | Fornece compressão maior que [CompressionLevel::Level7](./). |
| Level9 | 9 | Compressão máxima. Produz o menor tamanho de arquivo com a velocidade de processamento mais lenta. |

## Ver também

* Namespace [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)