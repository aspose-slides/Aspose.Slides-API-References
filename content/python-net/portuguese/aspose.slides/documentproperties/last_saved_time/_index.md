---
title: last_saved_time property
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/documentproperties/last_saved_time/
weight: 290
---
## last_saved_time propriedade
Retorna a data em que a apresentação foi modificada pela última vez.
            Os valores estão em UTC.
            Somente leitura no caso de Presentation.DocumentProperties (porque será atualizado internamente durante o processo de salvamento do objeto IPresentation). 
            Pode ser alterado via instância de DocumentProperties retornada pelo método [`IPresentationInfo.read_document_properties`](/slides/python-net/pt/aspose.slides/ipresentationinfo/read_document_properties)
            Por favor, veja o exemplo em **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** resumo do método.

### Definição:
```python
@property
def last_saved_time(self):
    ...

@last_saved_time.setter
def last_saved_time(self, value):
    ...
```


### Veja Também
* classe [`DocumentProperties`](/slides/python-net/pt/aspose.slides/documentproperties)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)