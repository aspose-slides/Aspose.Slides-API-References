---
title: compress_presentation method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
Reduz o tamanho de uma apresentação aplicando todas as etapas de compressão disponíveis:
            
* Remove slides mestres não usados **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* Remove slides de layout não usados **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* Mantém apenas os glifos realmente usados em fontes incorporadas **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* Reduz a resolução de imagens para 150 DPI e exclui áreas recortadas das imagens **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.


```python
@staticmethod
def compress_presentation(presentation):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/pt/aspose.slides/presentation) | A apresentação a ser comprimida. |

### Observações

Para personalizar a compressão, por exemplo para usar uma resolução de imagem diferente ou pular uma etapa,
            chame os métodos listados acima individualmente em vez deste.
            Áreas recortadas das imagens são removidas permanentemente e não podem ser restauradas no PowerPoint.

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` é `None`. |



### Veja Também
* classe [`Compress`](/slides/python-net/pt/aspose.slides.lowcode/compress)
* classe [`Presentation`](/slides/python-net/pt/aspose.slides/presentation)
* módulo [`aspose.slides.lowcode`](/slides/python-net/pt/aspose.slides.lowcode)
* biblioteca [`Aspose.Slides`](/slides/python-net)