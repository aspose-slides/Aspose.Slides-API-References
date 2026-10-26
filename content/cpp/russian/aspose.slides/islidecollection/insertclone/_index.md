---
title: InsertClone()
second_title: Справочник API Aspose.Slides для C++
description: Вставляет копию указанного слайда в указанную позицию коллекции.
type: docs
weight: 27
url: /ru/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) метод


Вставляет копию указанного слайда в указанную позицию коллекции.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```


### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Индекс нового слайда. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) для клонирования. |

### Возвращаемое значение

Inserted slide.
## Примечания



При клонировании слайда между различными презентациями мастер слайда также может быть клонирован. Внутренний реестр используется для отслеживания автоматически клонированных мастеров, чтобы предотвратить создание нескольких копий одного и того же мастера слайда. Ручное клонирование мастеров слайдов не будет ни предотвращено, ни зарегистрировано. Если требуется больший контроль над процессом клонирования, используйте [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) или [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) для клонирования слайдов и [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) для клонирования мастеров. 

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) метод


Вставляет копию указанного слайда в указанную позицию коллекции.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```


### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Индекс нового слайда. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) для клонирования. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Слайд макета для нового слайда. |

### Возвращаемое значение

Inserted slide.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) метод


Вставляет копию указанного исходного слайда в указанную позицию коллекции. Подходящий макет будет выбран автоматически из указанного мастера (подходящий макет — это макет с тем же Type или Name, что и макет исходного слайда). Если подходящего макета нет, то макет исходного слайда будет клонирован (если allowCloneMissingLayout истинно) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout ложно).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```


### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Индекс нового слайда. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) для клонирования. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master slide для нового слайда. |
| allowCloneMissingLayout | **bool** | Если в указанном мастере нет подходящего макета, то макет исходного слайда будет клонирован (если allowCloneMissingLayout истинно) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout ложно). |

### Возвращаемое значение

Inserted slide.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [ISlideCollection](../)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)