---
title: CopyPixelOperation
second_title: Aspose.Slides para C++ Referência da API
description: Especifica como a cor de origem em uma operação de cópia de pixel é combinada com a cor de destino para resultar em uma cor final.
type: docs
weight: 391
url: /pt/system.drawing/copypixeloperation/
---
## CopyPixelOperation enum

Especifica como a cor de origem em uma operação de cópia de pixel é combinada com a cor de destino para resultar em uma cor final.

```cpp
enum class CopyPixelOperation
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| NoMirrorBitmap | n/a | O bitmap não está espelhado. |
| Blackness | 66 | A região de destino é preenchida usando a cor com índice 0 na paleta física. |
| NotSourceErase | 1114278 | As cores de origem e destino são combinadas com OR e a cor resultante é então invertida. |
| NotSourceCopy | 3342344 | A região de origem é invertida e então copiada para o destino. |
| SourceErase | 4457256 | As cores invertidas da região de destino são combinadas com AND com as cores da região de origem. |
| DestinationInvert | 5570569 | A região de destino é invertida. |
| PatInvert | 5898313 | As cores do pincel atualmente selecionado no contexto de dispositivo de destino são combinadas com XOR com as cores do destino. |
| SourceInvert | 6684742 | As cores das regiões de origem e destino são combinadas com XOR. |
| SourceAnd | 8913094 | As cores das regiões de origem e destino são combinadas com AND. |
| MergePaint | 12255782 | As cores da região de origem invertida são combinadas com OR com as cores da região de destino. |
| MergeCopy | 12583114 | As cores da região de origem são combinadas com AND com as cores do pincel selecionado no contexto de dispositivo de destino. |
| SourceCopy | 13369376 | A região de origem é copiada diretamente para a região de destino. |
| SourcePaint | 15597702 | As cores das regiões de origem e destino são combinadas com OR. |
| PatCopy | 15728673 | O pincel atualmente selecionado no contexto de dispositivo de destino é copiado para o bitmap de destino. |
| PatPaint | 16452105 | As cores do pincel atualmente selecionado no contexto de dispositivo de destino são combinadas com OR com as cores da região de origem invertida. O resultado desta operação é combinado com OR com as cores da região de destino. |
| Whiteness | 16711778 | A região de destino é preenchida usando a cor com índice 1 na paleta física. |
| CaptureBlt | 1073741824 | [Windows](../../system.windows/) que são sobrepostas na janela da aplicação são incluídas na imagem resultante. |

## Veja Também

* Espaço de nomes [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)