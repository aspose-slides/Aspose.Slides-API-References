---
title: check_write_protection method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Verifica se a senha para modificar está correta em uma apresentação protegida contra gravação.

### Retorna

True se a apresentação estiver protegida contra gravação e a senha estiver correta. False caso contrário.



```python
def check_write_protection(self, password):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| password | **str** | The password to check. |

### Observações

1. Você deve verificar a propriedade [`PresentationInfo.is_write_protected`](/slides/python-net/pt/aspose.slides/presentationinfo/is_write_protected) antes de chamar este método.
2. Quando password for None ou estiver vazia, este método retorna false.

### Exceções

| Exceção | Descrição |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Ver também
* classe [`PresentationInfo`](/slides/python-net/pt/aspose.slides/presentationinfo)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)