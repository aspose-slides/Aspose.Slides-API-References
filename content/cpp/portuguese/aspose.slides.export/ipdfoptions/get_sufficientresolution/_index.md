---
title: get_SufficientResolution()
second_title: Referência da API Aspose.Slides para C++
description: Retorna um valor que determina a resolução das imagens dentro do documento PDF.
type: docs
weight: 313
url: /pt/aspose.slides.export/ipdfoptions/get_sufficientresolution/
---
## IPdfOptions::get_SufficientResolution() método

Retorna um valor que determina a resolução das imagens dentro do documento PDF.

```cpp
virtual float Aspose::Slides::Export::IPdfOptions::get_SufficientResolution()=0
```

## Observações

A propriedade afeta o tamanho do arquivo, o tempo de exportação e a qualidade da imagem.

O valor padrão é **96**.

O efeito deste parâmetro depende de alguns fatores. O algoritmo tenta obter o melhor tamanho de imagem de saída de acordo com o valor da propriedade, o tamanho da imagem de origem e o tamanho da moldura da imagem. O uso de valores de propriedade semelhantes pode gerar o mesmo resultado. Recomenda-se usar passos de 16 ou 32 para obter um efeito visível.

Ler **float**. 
## Consulte também

* Classe [IPdfOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)