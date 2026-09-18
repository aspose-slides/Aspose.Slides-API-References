---
title: check_write_protection method
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Determina se uma apresentação está protegida por senha para modificação.

### Retorna

True se a senha for válida; caso contrário, false.



```python
def check_write_protection(self, password):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| password | **str** | A senha para verificação. |

### Observações

1. Você deve verificar a propriedade [`IProtectionManager.is_write_protected`](/slides/python-net/pt/aspose.slides/iprotectionmanager/is_write_protected) antes de chamar este método.
2. Quando a senha for None ou vazia, este método retorna false.



### Ver também
* classe [`IProtectionManager`](/slides/python-net/pt/aspose.slides/iprotectionmanager)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)