---
title: save_metafiles_as_png property
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png propriedade
True para converter todos os metafiles usados em uma apresentação em imagens PNG.
            Leitura/ gravação **bool**.

### Observações
O padrão é **true** .
            Pdf document pode conter gráficos vetoriais e imagens raster.
            Se SaveMetafilesAsPng estiver definido como true então o Metafile de origem 
            imagem é convertida para o formato Png e salva no Pdf como uma imagem raster 
            . Se SaveMetafilesAsPng estiver definido como false então o Metafile de origem 
            é convertido para gráficos vetoriais do Pdf. Cada abordagem tem vantagens 
            e desvantagens. Por exemplo, se o Metafile for convertido para PNG, 
            então alguma perda de qualidade pode ocorrer durante o 
            dimensionamento do documento. Se o Metafile for convertido para gráficos vetoriais do Pdf, 
            então problemas de desempenho na ferramenta de visualização do Pdf são possíveis.

### Definição:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### Veja Também
* classe [`IPdfOptions`](/slides/python-net/pt/aspose.slides.export/ipdfoptions)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)