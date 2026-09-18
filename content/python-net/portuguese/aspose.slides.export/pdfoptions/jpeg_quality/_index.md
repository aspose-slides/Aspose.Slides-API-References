---
title: jpeg_quality property
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.export/pdfoptions/jpeg_quality/
weight: 160
---
## jpeg_quality propriedade
Retorna ou define um valor que determina a qualidade das imagens JPEG dentro do documento PDF.
            Leitura/gravação **int**.

### Observações

Tem efeito apenas quando um documento contém imagens JPEG.

Use esta propriedade para obter ou definir a qualidade das imagens dentro de um documento ao salvar no formato PDF.
            O valor pode variar de 0 a 100, onde 0 significa pior qualidade, mas compressão máxima, e 100 significa melhor qualidade, mas compressão mínima.

O valor padrão é **100** .

### Definição:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```

### Veja Também
* classe [`PdfOptions`](/slides/python-net/pt/aspose.slides.export/pdfoptions)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)