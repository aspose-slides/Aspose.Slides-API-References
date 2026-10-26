---
title: EmbeddingLevel
second_title: Referência da API Aspose.Slides para C++
description: Representa os direitos de licenciamento para incorporação da fonte.
type: docs
weight: 5786
url: /pt/aspose.slides/embeddinglevel/
---
## EmbeddingLevel enum


Representa os direitos de licenciamento para incorporação da fonte.

```cpp
enum class EmbeddingLevel : uint16_t
```

### Valores

| Name | Value | Description |
| --- | --- | --- |
| Installable | 0 | [Fonts](../fonts/) com esta configuração indica que podem ser incorporados e instalados permanentemente no sistema remoto por um aplicativo. O usuário do sistema remoto adquire os mesmos direitos, obrigações e licenças para essa fonte que o comprador original da fonte, e está sujeito ao mesmo contrato de licença de usuário final, direitos autorais, patente de design e/ou marca registrada que o comprador original. |
| Restricted | 2 | [Fonts](../fonts/) que têm apenas este bit definido não devem ser modificados, incorporados ou trocados de nenhuma forma sem antes obter permissão do proprietário legal. |
| PreviewPrint | 4 | Quando este bit está definido, a fonte pode ser incorporada e carregada temporariamente no sistema remoto. Documentos que contêm fontes Preview & Print devem ser abertos \"read-only;\" nenhuma edição pode ser aplicada ao documento. |
| Editable | 8 | Quando este bit está definido, a fonte pode ser incorporada, mas deve ser instalada temporariamente apenas em outros sistemas. Ao contrário das fontes Preview & Print, documentos que contêm fontes Editable podem ser abertos para leitura, a edição é permitida e as alterações podem ser salvas. |
| NoSubsetting | 256 | Quando este bit está definido, a fonte não pode ser subdefinida antes de ser incorporada. Outras restrições de incorporação especificadas nos bits 0-3 e 9 também se aplicam. |
| BitmapOnly | 512 | Quando este bit está definido, somente bitmaps contidos na fonte podem ser incorporados. Nenhum dado de contorno pode ser incorporado. Se não houver bitmaps disponíveis na fonte, então a fonte é considerada não incorporável e os serviços de incorporação falharão. |

## Veja Também

* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)