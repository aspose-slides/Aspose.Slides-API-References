---
title: app_version property
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/idocumentproperties/app_version/
weight: 90
---
## app_version propriedade
Retorna a versão do app.
            Somente leitura **str**.

### Observações

O conteúdo deste elemento deve estar no formato XX.YYYY, onde X e Y representam valores numéricos;
            caso contrário, o documento será considerado não conformante.
            Aspose.Slides representa sua versão no formato XX.YYZZ, onde:
            XX - versão principal
            YY - versão secundária
            ZZ - versão patch
            Por exemplo, o valor 23.0105 significa a versão Aspose.Slides 23.1.5.

### Definição:
```python
@property
def app_version(self):
    ...
```

### Ver também
* classe [`IDocumentProperties`](/slides/python-net/pt/aspose.slides/idocumentproperties)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)