---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides para C++ Referência da API
description: Verdadeiro para converter todos os metafiles usados em uma apresentação para imagens PNG. Escreva bool.
type: docs
weight: 300
url: /pt/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) método

Verdadeiro para converter todos os Metafiles usados em uma apresentação em imagens PNG. Escreva **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## Observações

O padrão é **true**. Um documento Pdf pode conter gráficos vetoriais e imagens raster. Se SaveMetafilesAsPng estiver definido como true, a imagem Metafile de origem será convertida para o formato Png e salva no Pdf como uma imagem raster. Se SaveMetafilesAsPng estiver definido como false, o Metafile de origem será convertido em gráficos vetoriais do Pdf. Cada abordagem tem vantagens e desvantagens. Por exemplo, se o Metafile for convertido para PNG, alguma perda de qualidade pode ocorrer durante o dimensionamento do documento resultante. Se o Metafile for convertido em gráficos vetoriais do Pdf, podem ocorrer problemas de desempenho na ferramenta de visualização do Pdf.

## Veja Também

* Classe [IPdfOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)