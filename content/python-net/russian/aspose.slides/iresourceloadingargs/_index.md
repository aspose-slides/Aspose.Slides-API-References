---
title: IResourceLoadingArgs class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/iresourceloadingargs/
---
## IResourceLoadingArgs класс

Интерфейс для аргументов загрузки внешних ресурсов.

Тип IResourceLoadingArgs предоставляет следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`original_uri`](/slides/python-net/ru/aspose.slides/iresourceloadingargs/original_uri/) | Исходный URI ресурса, указанный в импортированной презентации. |
| [`uri`](/slides/python-net/ru/aspose.slides/iresourceloadingargs/uri/) | URI ресурса, который используется для загрузки, если **Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** <br/> возвращает [`ResourceLoadingAction.DEFAULT`](/slides/python-net/ru/aspose.slides/resourceloadingaction/DEFAULT). <br/> Изначально он установлен на исходный URI ресурса, но может быть переопределён любым значением. |

## Методы

| Метод | Описание |
| :- | :- |
| [`set_data(self, data)`](/slides/python-net/ru/aspose.slides/iresourceloadingargs/set_data/#bytes) | Устанавливает пользовательские данные ресурса, которые используются, если **Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** <br/> возвращает [`ResourceLoadingAction.USER_PROVIDED`](/slides/python-net/ru/aspose.slides/resourceloadingaction/USER_PROVIDED). |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)