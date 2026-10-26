---
title: set_license method
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
Licencia o componente.

```python
def set_license(self, license_name):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| license_name | **str** | Pode ser um nome de arquivo completo ou abreviado ou o nome de um recurso incorporado.<br/><br/>            Use uma string vazia para mudar para o modo de avaliação. |

### Observações

Tenta encontrar a licença nos seguintes locais:

1. Caminho explícito.

2. A pasta da montagem do componente.

3. A pasta da montagem de chamada do cliente.

4. A pasta da montagem de entrada.

5. Um recurso incorporado na montagem de chamada do cliente.

**Nota:** No .NET Compact Framework, tenta encontrar a licença somente nestes locais:

1. Caminho explícito.

2. Um recurso incorporado na montagem de chamada do cliente.

## set_license(self, stream) {#iorawiobase}
Licencia o componente.

```python
def set_license(self, stream):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Um fluxo que contém a licença. |

### Observações

Use este método para carregar uma licença a partir de um fluxo.



### Veja Também
* classe [`ILicense`](/slides/python-net/pt/aspose.slides/ilicense)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)