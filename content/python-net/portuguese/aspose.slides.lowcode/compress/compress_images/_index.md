---
title: compress_images method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
Reduz a resolução das imagens na apresentação e exclui suas áreas recortadas,
similar ao "Compress Pictures" do PowerPoint aplicado a todas as imagens.
Imagens em slides, slides de layout e slides mestre são processadas, incluindo imagens dentro de formas agrupadas
e preenchimentos de forma com imagens.

```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation) | A apresentação a ser processada. |
| resolution | [`PicturesCompression`](/slides/python-net/pt/aspose.slides.export/picturescompression) | Resolução alvo relativa ao tamanho em que cada imagem é exibida.<br/><br/>            [`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/pt/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) deixa as imagens inalteradas. |

### Observações

Imagens já na resolução alvo ou inferior permanecem inalteradas; as imagens nunca são ampliadas.

Não processados: fundos de slide, preenchimentos de células de tabela, gráficos, SmartArt, imagens GIF (para preservar animação),
SVG e imagens de metafile (EMF/WMF).

Áreas recortadas são removidas permanentemente e não podem ser restauradas no PowerPoint.

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` é `None`. |

### Veja Também
* classe [`Compress`](/slides/python-net/pt/aspose.slides.lowcode/compress)
* classe [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation)
* enumeração [`PicturesCompression`](/slides/python-net/pt/aspose.slides.export/picturescompression)
* módulo [`aspose.slides.lowcode`](/slides/python-net/pt/aspose.slides.lowcode)
* biblioteca [`Aspose.Slides`](/slides/python-net)