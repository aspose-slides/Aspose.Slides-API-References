---
title: set_license method
second_title: Referência de API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/license/set_license/
weight: 40
---
## set_license(self, license_name) {#str}
Licencia o componente.

```python
def set_license(self, license_name):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| license_name | **str** | Pode ser um nome de arquivo completo ou curto ou o nome de um recurso incorporado.<br/><br/>Use uma string vazia para mudar para o modo de avaliação. |

### Observações

Tenta localizar a licença nos seguintes locais:

1. Caminho explícito.
2. A pasta da assembly do componente.
3. A pasta da assembly de chamada do cliente.
4. A pasta da assembly de entrada.
5. Um recurso incorporado na assembly de chamada do cliente.

**Observação:** No .NET Compact Framework, tenta localizar a licença apenas nesses locais:

1. Caminho explícito.
2. Um recurso incorporado na assembly de chamada do cliente.

## set_license(self, stream) {#iorawiobase}
Licencia o componente.

```python
def set_license(self, stream):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| stream | **io.RawIOBase** | Um stream que contém a licença. |

### Observações

Use este método para carregar uma licença a partir de um stream.

### Veja Também
* classe [`License`](/slides/python-net/pt/aspose.slides/license)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)