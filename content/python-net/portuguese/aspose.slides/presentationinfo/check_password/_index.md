---
title: check_password method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
Verifica se uma senha está correta para uma apresentação protegida com senha aberta.

### Returns
Retorna True se a apresentação estiver protegida com senha aberta e a senha estiver correta e False caso contrário.



```python
def check_password(self, password):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| password | **str** | A senha a ser verificada. |

### Remarks
Quando a senha for None ou vazia, este método retorna false.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |



### See Also
* classe [`PresentationInfo`](/slides/python-net/pt/aspose.slides/presentationinfo)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)