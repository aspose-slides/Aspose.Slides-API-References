---
title: get_url method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
Retorna um URL para um objeto externo.
            Este método sempre é chamado se **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** retornou [`LinkEmbedDecision.LINK`](/slides/python-net/pt/aspose.slides.export/linkembeddecision/LINK) e pode ser chamado se **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** retornou [`LinkEmbedDecision.EMBED`](/slides/python-net/pt/aspose.slides.export/linkembeddecision/EMBED) mas a incorporação é impossível.
            Pode ser chamado várias vezes para o mesmo id de objeto.

### Retorno

Url do objeto externo ou None se este objeto deve ser ignorado.



```python
def get_url(self, id, referrer):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| id | **int** | Id do objeto. Este id é único em toda a operação de salvamento. |
| referrer | **int** | Id do objeto de referência ou 0, se o objeto for referenciado pelo documento raiz. Pode ser usado para gerar link relativo. |



### Veja Também
* classe [`ILinkEmbedController`](/slides/python-net/pt/aspose.slides.export/ilinkembedcontroller)
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)