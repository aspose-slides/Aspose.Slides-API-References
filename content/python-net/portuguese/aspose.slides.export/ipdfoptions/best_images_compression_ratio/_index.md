---
title: best_images_compression_ratio property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.export/ipdfoptions/best_images_compression_ratio/
weight: 50
---
## best_images_compression_ratio propriedade
Indica se a compressão mais eficaz (em vez da padrão) para cada imagem deve ser selecionada automaticamente. Se definido como **bool**.true, para cada imagem na apresentação o algoritmo de compressão mais apropriado será escolhido, o que levará a um tamanho menor do documento PDF resultante. A seleção da melhor taxa de compressão de imagens é computacionalmente cara e consome uma quantidade adicional de RAM, e esta opção é **bool**.false por padrão.

### Observações

O padrão é **bool**.false.

### Definição:
```python
@property
def best_images_compression_ratio(self):
    ...

@best_images_compression_ratio.setter
def best_images_compression_ratio(self, value):
    ...
```

### Veja Também
* classe [`IPdfOptions`](/slides/python-net/pt/aspose.slides.export/ipdfoptions)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)