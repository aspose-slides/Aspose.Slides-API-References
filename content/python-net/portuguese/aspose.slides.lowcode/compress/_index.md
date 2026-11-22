---
title: Compress class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.lowcode/compress/
---
## Classe Compress

Representa um grupo de métodos destinados a compactar [`Presentation`](/slides/python-net/pt/aspose.slides/presentation).

O tipo Compress expõe os seguintes membros:

## Métodos

| Método | Descrição |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/pt/aspose.slides.lowcode/compress/compress_presentation/#presentation) | Reduz o tamanho de uma apresentação aplicando todas as etapas de compressão disponíveis:<br/>            <br/>* Remove slides mestres não utilizados **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* Remove slides de layout não utilizados **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* Mantém apenas os glifos realmente usados em fontes incorporadas **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* Reduz a resolução das imagens para 150 DPI e exclui áreas recortadas das imagens **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/pt/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | Realiza a compressão do [`Presentation`](/slides/python-net/pt/aspose.slides/presentation) removendo slides mestres não utilizados. |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/pt/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | Realiza a compressão do [`Presentation`](/slides/python-net/pt/aspose.slides/presentation) removendo slides de layout não utilizados. |
| [`compress_embedded_fonts(pres)`](/slides/python-net/pt/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | Realiza a compressão do [`Presentation`](/slides/python-net/pt/aspose.slides/presentation) removendo caracteres não utilizados de fontes incorporadas. |
| [`compress_images(presentation, resolution)`](/slides/python-net/pt/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | Reduz a resolução das imagens na apresentação e exclui suas áreas recortadas,<br/>            semelhante ao "Compress Pictures" do PowerPoint aplicado a todas as imagens.<br/>            Imagens em slides, slides de layout e slides mestres são processadas, incluindo imagens dentro de formas de grupo<br/>            e preenchimentos de imagem de formas. |

### Veja Também
* classe [`Presentation`](/slides/python-net/pt/aspose.slides/presentation)
* módulo [`aspose.slides.lowcode`](/slides/python-net/pt/aspose.slides.lowcode)
* biblioteca [`Aspose.Slides`](/slides/python-net)