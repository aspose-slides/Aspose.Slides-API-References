---
title: EmbeddingLevel enumeration
second_title: Aspose.Slides para Python via Referência da API .NET
description: 
type: docs
url: /pt/aspose.slides/embeddingleid/
---
## Enumeração EmbeddingLevel

Representa os direitos de licença para incorporação da fonte.

O tipo EmbeddingLevel expõe os seguintes membros:

## Campos

| Campo | Descrição |
| :- | :- |
| INSTALLABLE | Fontes com esta configuração indicam que podem ser incorporadas e instaladas permanentemente no sistema remoto por um aplicativo. <br/>            O usuário do sistema remoto adquire os direitos, obrigações e licenças idênticos para essa fonte como o comprador original da fonte, <br/>            e está sujeito ao mesmo acordo de licença de usuário final, direitos autorais, patente de design e/ou marca registrada que o comprador original. |
| RESTRICTED | Fontes que têm apenas este bit definido não devem ser modificadas, incorporadas ou trocadas de nenhuma forma sem antes obter permissão do proprietário legal. |
| PREVIEW_PRINT | Quando este bit está definido, a fonte pode ser incorporada e carregada temporariamente no sistema remoto. Documentos contendo fontes Preview & <br/>            Print devem ser abertos "somente leitura"; nenhuma edição pode ser aplicada ao documento. |
| EDITABLE | Quando este bit está definido, a fonte pode ser incorporada, mas deve ser instalada temporariamente apenas em outros sistemas. Ao contrário das fontes Preview & <br/>            Print, documentos contendo fontes Editable podem ser abertos para leitura, a edição é permitida e as alterações podem ser salvas. |
| NO_SUBSETTING | Quando este bit está definido, a fonte não pode ser subconjuntada antes da incorporação. Outras restrições de incorporação especificadas nos bits 0-3 e 9 também se aplicam. |
| BITMAP_ONLY | Quando este bit está definido, apenas bitmaps contidos na fonte podem ser incorporados. Nenhum dado de contorno pode ser incorporado. Se não houver bitmaps disponíveis na fonte, <br/>            então a fonte é considerada não incorporável e os serviços de incorporação falharão. |


### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)