---
title: is_visible property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.charts/datalabelcollection/is_visible/
weight: 130
---
## is_visible property
False significa que o rótulo de dados não está visível por padrão (e, portanto, todas as flags Show*-flags (ShowValue, ...) da propriedade DefaultDataLabelFormat são false). Somente leitura **bool**.

### Observações

Se o rótulo de dados estiver visível por padrão, você pode torná-lo oculto por padrão com o método Hide().
Mas se o rótulo de dados não estiver visível por padrão (IsVisible é false) você pode tornar o rótulo de dados "visível 
por padrão" configurando as flags Show*-flags (ShowValue, ...) da propriedade DefaultDataLabelFormat
para o estado true.

### Definição:
```python
@property
def is_visible(self):
    ...
```

### Veja também
* classe [`DataLabelCollection`](/slides/python-net/pt/aspose.slides.charts/datalabelcollection)
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)