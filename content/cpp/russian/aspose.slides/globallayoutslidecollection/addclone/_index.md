---
title: AddClone()
second_title: Aspose.Slides для C++ справки API
description: Добавляет копию указанного макетного слайда в презентацию.
type: docs
weight: 1
url: /ru/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method

Добавляет копию указанного макета слайда в презентацию.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) для клонирования. |

### Return Value

Добавленный слайд.

## Remarks

При клонировании макета между разными презентациями мастер-макет может быть клонирован также, чтобы сохранить исходное форматирование. Внутренний реестр используется для автоматического отслеживания клонированных мастеров, чтобы предотвратить создание нескольких копий одного и того же мастера. Ручное клонирование мастер-слайдов не будет ни предотвращено, ни зарегистрировано. 

## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) method

Добавляет копию указанного макета слайда в презентацию.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) для клонирования. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Мастер-слайд для нового макета. |

### Return Value

Добавленный слайд.

## Remarks

1) Новый макет будет связан с определённым мастером в целевой презентации. Таким образом это аналог копирования/вставки с опцией \"Use Destination Theme\" в PowerPoint. 2) Аналогом этого метода является метод [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/), доступный через свойство [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/). 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [GlobalLayoutSlideCollection](../)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)