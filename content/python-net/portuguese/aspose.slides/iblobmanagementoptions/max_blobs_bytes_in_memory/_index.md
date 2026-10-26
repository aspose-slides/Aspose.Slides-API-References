---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory propriedade
Define o tamanho total máximo (em bytes) que todos os BLOBs podem ocupar na memória. Por padrão, todos os BLOBs
            são carregados na memória; somente quando esse limite é atingido são empregados mecanismos alternativos (como arquivos temporários). Manter os BLOBs na memória maximiza o desempenho, mas pode levar a alto uso de memória. Use
            esta propriedade para adaptar o comportamento ao seu ambiente ou requisitos.


### Observações

Esta propriedade é ignorada se [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/pt/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) for definido como false, pois a memória é então
            o único local de armazenamento disponível e limitar o uso de BLOBs na memória não tem efeito.

### Definição:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```


### Veja Também
* classe [`IBlobManagementOptions`](/slides/python-net/pt/aspose.slides/iblobmanagementoptions)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)