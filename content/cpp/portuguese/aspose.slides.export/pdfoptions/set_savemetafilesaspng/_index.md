---
title: set_SaveMetafilesAsPng()
second_title: Referência da API Aspose.Slides para C++
description: True para converter todos os metafiles usados em uma apresentação em imagens PNG. Write bool.
type: docs
weight: 339
url: /pt/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) método


True para converter todos os metafiles usados em uma apresentação em imagens PNG. Escreva **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## Observações


O padrão é **true**. Um documento Pdf pode conter gráficos vetoriais e imagens raster. Se SaveMetafilesAsPng estiver definido como true, então a imagem Metafile de origem é convertida para o formato Png e salva no Pdf como imagem raster. Se SaveMetafilesAsPng estiver definido como false, então o Metafile de origem é convertido em gráficos vetoriais Pdf. Cada abordagem tem vantagens e desvantagens. Por exemplo, se o Metafile for convertido para PNG, pode haver alguma perda de qualidade durante a escala do documento resultante. Se o Metafile for convertido em gráficos vetoriais Pdf, podem ocorrer problemas de desempenho na ferramenta de visualização Pdf. 
## Veja Também

* Classe [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)