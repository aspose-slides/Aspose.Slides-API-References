---
title: jpeg_quality property
second_title: Referência de API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.export/htmloptions/jpeg_quality/
weight: 90
---
## jpeg_quality propriedade
Retorna ou define um valor que determina a qualidade das imagens JPEG dentro do documento PDF.
            Leitura/gravação **int**.


### Observações

Tem efeito somente quando um documento contém imagens JPEG.


Use esta propriedade para obter ou definir a qualidade das imagens dentro de um documento ao salvar no formato PDF.
            O valor pode variar de 0 a 100, onde 0 significa a pior qualidade mas compressão máxima e 100 significa a melhor qualidade mas compressão mínima.


O valor padrão é **95** .

### Definição:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```


### Veja também
* classe [`HtmlOptions`](/slides/python-net/pt/aspose.slides.export/htmloptions)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)