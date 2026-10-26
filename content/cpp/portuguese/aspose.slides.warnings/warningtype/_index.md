---
title: WarningType
second_title: Referência da API Aspose.Slides para C++
description: Representa um tipo de aviso.
type: docs
weight: 92
url: /pt/aspose.slides.warnings/warningtype/
---
## WarningType enum

Representa um tipo de aviso.

```cpp
enum class WarningType
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| SourceFileCorruption | 0 | Foi detectado um problema no documento de origem que torna muito provável que o documento não possa ser aberto se for salvo em seu formato original. |
| DataLoss | 1 | Texto/gráfico/imagem ou outros dados ficarão completamente ausentes tanto da árvore do documento após o carregamento quanto do documento criado após a gravação. |
| MajorFormattingLoss | 2 | Perda significativa de formatação. |
| MinorFormattingLoss | 3 | Perda menor de formatação. |
| CompatibilityIssue | 4 | Este é um problema conhecido que impedirá a abertura do documento por determinados agentes de usuário ou versões anteriores desses agentes. |
| UnexpectedContent | 99 | Algum conteúdo no documento de origem não pôde ser reconhecido (ou seja, não é suportado); isso pode ou não causar problemas ou resultar em perda de dados/formatação. |

## Veja Também

* Namespace [Aspose::Slides::Warnings](../)
* Biblioteca [Aspose.Slides](../../)