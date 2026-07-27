---
title: HandleRepeatedSpaces
second_title: Referência da API Aspose.Slides para C++
description: Especifica como os caracteres de espaço regular repetidos devem ser tratados durante a exportação para Markdown.
type: docs
weight: 937
url: /pt/aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces enum


Especifica como os caracteres de espaço regular repetidos devem ser tratados durante a exportação para Markdown.

```cpp
enum class HandleRepeatedSpaces
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| None | 0 | Todos os espaços são preservados como caracteres de espaço normais sem quaisquer alterações. Nenhuma transformação é aplicada, e múltiplos espaços consecutivos são exportados como estão. |
| AlternateSpacesToNbsp | 1 | Converte sequências de dois ou mais espaços regulares consecutivos alternando entre caracteres de espaço normais e entidades de espaço não-quebrável (**&nbsp;**). O primeiro espaço é sempre preservado como espaço regular. |
| MultipleSpacesToNbsp | 2 | Converte sequências de dois ou mais espaços regulares consecutivos preservando o primeiro espaço como caracter de espaço regular e substituindo todos os espaços subsequentes por entidades de espaço não-quebrável (**&nbsp;**). |

## Veja Também

* Espaço de nomes [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)