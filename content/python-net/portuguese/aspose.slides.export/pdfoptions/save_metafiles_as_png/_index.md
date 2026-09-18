---
title: save_metafiles_as_png property
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png propriedade
True para converter todos os metafiles usados em uma apresentação para imagens PNG.
            Leitura/gravação **bool**.


### Observações

O padrão é **true** .
            Um documento Pdf pode conter gráficos vetoriais e imagens raster. 
            Se SaveMetafilesAsPng estiver definido como true então a imagem Metafile de origem 
            é convertida para o formato Png e salva no Pdf como uma imagem raster. 
            Se SaveMetafilesAsPng estiver definido como false então a Metafile de origem 
            é convertida para gráficos vetoriais Pdf. Cada abordagem tem vantagens 
            e desvantagens. Por exemplo, se Metafile for convertido para PNG, 
            então alguma perda de qualidade pode ocorrer durante o dimensionamento 
            do documento resultante. Se Metafile for convertido para gráficos vetoriais Pdf, 
            então problemas de desempenho na ferramenta de visualização de Pdf são possíveis.

### Definição:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```


### See Also
* classe [`PdfOptions`](/slides/python-net/pt/aspose.slides.export/pdfoptions)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)