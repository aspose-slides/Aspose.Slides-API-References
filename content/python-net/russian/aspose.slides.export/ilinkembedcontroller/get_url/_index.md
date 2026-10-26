---
title: get_url method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.export/ilinkembedcontroller/get_url/
weight: 20
---
## get_url(self, id, referrer) {#int-int}
Возвращает URL внешнего объекта.
            Этот метод всегда вызывается, если **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** вернул [`LinkEmbedDecision.LINK`](/slides/python-net/ru/aspose.slides.export/linkembeddecision/LINK) и может быть вызван, если **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** вернул [`LinkEmbedDecision.EMBED`](/slides/python-net/ru/aspose.slides.export/linkembeddecision/EMBED), но внедрение невозможно.
            Может быть вызван многократно для одного и того же идентификатора объекта.

### Возвращаемое значение

URL внешнего объекта или None, если этот объект следует игнорировать.



```python
def get_url(self, id, referrer):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| id | **int** | Идентификатор объекта. Этот идентификатор уникален в рамках операции сохранения. |
| referrer | **int** | Идентификатор ссылающегося объекта или 0, если объект ссылается корневой документ. Может использоваться для создания относительной ссылки. |



### См. также
* класс [`ILinkEmbedController`](/slides/python-net/ru/aspose.slides.export/ilinkembedcontroller)
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)