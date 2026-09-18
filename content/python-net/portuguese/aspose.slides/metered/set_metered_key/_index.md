---
title: set_metered_key method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/metered/set_metered_key/
weight: 60
---
## set_metered_key(self, public_key, private_key) {#str-str}
Define a chave pública e privada de medição. Se você comprar uma licença de medição, ao iniciar a aplicação, esta API deve ser chamada; normalmente, isso é suficiente. No entanto, se falhar sempre ao enviar dados de consumo e exceder 24 horas, a licença será definida como status de avaliação. Para evitar esse caso, você deve verificar regularmente o status da licença; se estiver em status de avaliação, chame esta API novamente.

```python
def set_metered_key(self, public_key, private_key):
    ...
```

| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| public_key | **str** | chave pública |
| private_key | **str** | chave privada |

### See Also
* classe [`Metered`](/slides/python-net/pt/aspose.slides/metered)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)