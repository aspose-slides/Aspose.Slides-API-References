---
title: check_write_protection method
second_title: Aspose.Slides para Python via .NET - Referência da API
description: 
type: docs
url: /pt/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Determina se uma apresentação está protegida por senha para modificar.

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

1. Você deve verificar a propriedade [`ProtectionManager.is_write_protected`](/slides/python-net/pt/aspose.slides/protectionmanager/is_write_protected) antes de chamar este método.
2. Quando o password for None ou vazio, este método retorna false.



### Veja Também
* classe [`ProtectionManager`](/slides/python-net/pt/aspose.slides/protectionmanager)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)