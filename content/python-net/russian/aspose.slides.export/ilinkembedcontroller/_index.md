---
title: ILinkEmbedController class
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController класс

Обратный интерфейс используется для определения того, как объект должен обрабатываться при сохранении.

Тип ILinkEmbedController раскрывает следующие члены:

## Методы

| Метод | Описание |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/ru/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | Determines where object should be stored.<br/>            This method is called once for each object id.<br/>            It is not guaranteed that there won't be two objects with same data, semanticName and contentType but with different id. |
| [`get_url(self, id, referrer)`](/slides/python-net/ru/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | Returns an URL to an external object.<br/>            This method always called if **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** returned [`LinkEmbedDecision.LINK`](/slides/python-net/ru/aspose.slides.export/linkembeddecision/LINK) and may be called if **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** returned [`LinkEmbedDecision.EMBED`](/slides/python-net/ru/aspose.slides.export/linkembeddecision/EMBED) but embedding is impossible.<br/>            Can be called multiple time for same object id. |
| [`save_external(self, id, entity_data)`](/slides/python-net/ru/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | Saves external object. |


### См. также
* модуль [`aspose.slides.export`](/slides/python-net/ru/aspose.slides.export)
* библиотека [`Aspose.Slides`](/slides/python-net)