---
title: set_SufficientResolution()
second_title: Referência da API Aspose.Slides para C++
description: Define um valor que determina a resolução das imagens dentro do documento PDF.
type: docs
weight: 326
url: /pt/aspose.slides.export/ipdfoptions/set_sufficientresolution/
---
## IPdfOptions::set_SufficientResolution(float) método


Define um valor que determina a resolução das imagens dentro do documento PDF.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SufficientResolution(float value)=0
```

## Observações


A propriedade afeta o tamanho do arquivo, o tempo de exportação e a qualidade da imagem.

O valor padrão é **96**.

O efeito deste parâmetro depende de alguns fatores. O algoritmo tenta obter o melhor tamanho de imagem de saída de acordo com o valor da propriedade, o tamanho da imagem original e o tamanho da moldura da imagem. O uso de valores de propriedade semelhantes pode gerar o mesmo resultado. Recomenda-se usar passos de 16 ou 32 para obter um efeito visível.

Escreva **float**. 
## Ver também

* Classe [IPdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)