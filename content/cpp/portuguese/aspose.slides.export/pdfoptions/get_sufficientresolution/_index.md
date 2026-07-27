---
title: get_SufficientResolution()
second_title: Aspose.Slides para C++ Referência da API
description: Retorna um valor que determina a resolução das imagens dentro do documento PDF.
type: docs
weight: 352
url: /pt/aspose.slides.export/pdfoptions/get_sufficientresolution/
---
## PdfOptions::get_SufficientResolution() método

Retorna um valor que determina a resolução das imagens dentro do documento PDF.

```cpp
float Aspose::Slides::Export::PdfOptions::get_SufficientResolution() override
```

## Observações

A propriedade afeta o tamanho do arquivo, o tempo de exportação e a qualidade da imagem.

O valor padrão é **96**.

O efeito deste parâmetro depende de alguns fatores. O algoritmo tenta obter o melhor tamanho de imagem de saída de acordo com o valor da propriedade, o tamanho da imagem original e o tamanho da moldura da imagem. O uso de valores de propriedade semelhantes pode gerar o mesmo resultado. Recomenda-se usar passo 16 ou 32 para obter um efeito visível.

Leitura **float**. 
## Ver também

* Classe [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)