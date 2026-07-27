---
title: Zip64Mode
second_title: Referência da API Aspose.Slides para C++
description: Especifica quando usar extensões de formato ZIP64 para arquivos OpenXML.
type: docs
weight: 1119
url: /pt/aspose.slides.export/zip64mode/
---
## Zip64Mode enum

Especifica quando usar extensões de formato ZIP64 para arquivos OpenXML.

```cpp
enum class Zip64Mode
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Never | 0 | Não use extensões de formato ZIP64. |
| IfNecessary | 1 | Use extensões de formato ZIP64 se necessário. |
| Always | 2 | Sempre use extensões de formato ZIP64. |

## Observações

O arquivo OpenXML é um arquivo ZIP que tem um limite de 4 GB (2^32 bytes) para o tamanho descompactado de um arquivo, tamanho compactado de um arquivo e tamanho total do arquivo, bem como um limite de 65.535 (2^16-1) arquivos no arquivo. As extensões de formato ZIP64 aumentam os limites para 2^64. 

## Veja Também

* Espaço de nomes [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)