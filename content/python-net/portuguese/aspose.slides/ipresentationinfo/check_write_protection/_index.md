---
title: check_write_protection method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Verifica se a senha para modificar está correta em uma apresentação protegida contra gravação.

### Retorno

True if the presentation is write protected and the password is correct. False otherwise.



```python
def check_write_protection(self, password):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| password | **str** | The password to check. |

### Observações

1. Você deve verificar a propriedade [`IPresentationInfo.is_write_protected`](/slides/python-net/pt/aspose.slides/ipresentationinfo/is_write_protected) antes de chamar este método.
2. Quando password for None ou vazio, este método retorna false.

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Veja Também
* classe [`IPresentationInfo`](/slides/python-net/pt/aspose.slides/ipresentationinfo)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)