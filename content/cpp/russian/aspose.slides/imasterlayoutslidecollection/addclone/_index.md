---
title: AddClone()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет копию указанного слайда макета в конец коллекции.
type: docs
weight: 1
url: /ru/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) метод


Добавляет копию указанного слайда макета в конец коллекции.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) для клонирования. |

### Возвращаемое значение

Добавленный слайд.
## Примечания



1) Новый макет будет связан с родительским мастер-слайдом для данной коллекции слайдов макета. Таким образом, это аналог копирования/вставки с параметром \"Use Destination Theme\" в PowerPoint. 2) Аналогом этого метода является метод [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/), доступный через свойство [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/). 
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)