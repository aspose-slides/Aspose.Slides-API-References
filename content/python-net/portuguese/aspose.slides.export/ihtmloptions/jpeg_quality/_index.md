---
title: jpeg_quality property
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.export/ihtmloptions/jpeg_quality/
weight: 80
---
## jpeg_quality propriedade
Retorna ou define um valor que determina a qualidade das imagens JPEG dentro de um documento PDF.
            Leitura/gravação **int**.


### Observações

Tem efeito apenas quando um documento contém imagens JPEG.


Use esta propriedade para obter ou definir a qualidade das imagens dentro de um documento ao salvar no formato PDF.
            O valor pode variar de 0 a 100, onde 0 significa pior qualidade mas compressão máxima e 100 significa melhor qualidade mas compressão mínima.


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
* classe [`IHtmlOptions`](/slides/python-net/pt/aspose.slides.export/ihtmloptions)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)