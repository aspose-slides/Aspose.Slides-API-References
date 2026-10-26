---
title: presentation_locking_behavior property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/
weight: 30
---
## presentation_locking_behavior propriedade
Esta propriedade define se uma instância da classe Presentation pode ser proprietária da origem - arquivo ou stream durante a vida útil da instância. Se a instância for proprietária, ela bloqueia a origem. Isso ajuda a melhorar o consumo de memória e o desempenho ao trabalhar com BLOBs, mas a origem (stream ou arquivo) não pode ser alterada durante a vida útil da instância da Presentation. Este é um exemplo:

### Definição:
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```


### Ver também
* classe [`IBlobManagementOptions`](/slides/python-net/pt/aspose.slides/iblobmanagementoptions)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)