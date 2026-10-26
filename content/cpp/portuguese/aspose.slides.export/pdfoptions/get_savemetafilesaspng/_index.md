---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides para C++ Referência da API
description: True para converter todos os metafiles usados em uma apresentação para as imagens PNG. Leia bool.
type: docs
weight: 326
url: /pt/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() método


True para converter todos os metafiles usados em uma apresentação para as imagens PNG. Leia **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## Observações


Default é **true**. O documento Pdf pode conter gráficos vetoriais e imagens rasterizadas. Se SaveMetafilesAsPng estiver definido como true então a imagem Metafile de origem é convertida para o formato Png e salva no Pdf como uma imagem raster. Se SaveMetafilesAsPng estiver definido como false então o Metafile de origem é convertido para gráficos vetoriais Pdf. Cada abordagem tem vantagens e desvantagens. Por exemplo, se o Metafile for convertido para PNG, então alguma perda de qualidade pode ocorrer durante o dimensionamento do documento resultante. Se o Metafile for convertido para gráficos vetoriais Pdf, então podem ocorrer problemas de desempenho na ferramenta de visualização Pdf. 
## Veja Também

* Classe [PdfOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)