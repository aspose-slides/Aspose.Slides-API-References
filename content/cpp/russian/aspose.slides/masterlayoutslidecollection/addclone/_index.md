---
title: AddClone()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет копию указанного макетного слайда в конец коллекции.
type: docs
weight: 1
url: /ru/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method

Добавляет копию указанного макетного слайда в конец коллекции.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) для клонирования. |

### Return Value

Добавленный слайд.

## Remarks

1) Новый макет будет связан с родительским мастер-слайдом для этой коллекции слайдов макета. Таким образом, это аналог копирования/вставки с опцией \"Use Destination Theme\" в PowerPoint. 2) Аналогом этого метода является метод [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/), доступный через свойство [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/). 

## See Also

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [ILayoutSlide](../../ilayoutslide/)
* Класс [MasterLayoutSlideCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)