---
title: get_SaveMetafilesAsPng()
second_title: Referência da API Aspose.Slides para C++
description: True para converter todos os metafiles usados em uma apresentação para imagens PNG. Ler bool.
type: docs
weight: 287
url: /pt/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() método


True para converter todos os metafiles usados em uma apresentação para imagens PNG. Ler **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## Observações


O padrão é **true**. O documento Pdf pode conter gráficos vetoriais e imagens raster. Se SaveMetafilesAsPng estiver definido como true, então a imagem Metafile de origem é convertida para o formato Png e salva no Pdf como uma imagem raster. Se SaveMetafilesAsPng estiver definido como false, então o Metafile de origem é convertido para gráficos vetoriais Pdf. Cada abordagem tem vantagens e desvantagens. Por exemplo, se o Metafile for convertido para PNG, então alguma perda de qualidade pode ocorrer durante o dimensionamento do documento resultante. Se o Metafile for convertido para gráficos vetoriais Pdf, então problemas de desempenho na ferramenta de visualização do Pdf são possíveis. 
## Veja Também

* Classe [IPdfOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)