---
title: InsertClone()
second_title: Aspose.Slides для C++ справка по API
description: Вставляет копию указанного слайда в указанную позицию коллекции.
type: docs
weight: 66
url: /ru/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) метод


Вставляет копию указанного слайда в указанную позицию коллекции.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс нового слайда. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) для клонирования. |

### Возвращаемое значение

Вставленный слайд.

## Замечания



При клонировании слайда между разными презентациями мастер-слайд также может быть клонирован. Внутренний реестр используется для отслеживания автоматически клонированных мастеров, чтобы предотвратить создание нескольких копий одного и того же мастер-слайда. Ручное клонирование мастер-слайдов не будет ни предотвращено, ни зарегистрировано. Если требуется больший контроль над процессом клонирования, используйте [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) или [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) для клонирования слайдов и [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) для клонирования мастеров. 


Следующий пример показывает, как клонировать в другую позицию внутри [Presentation](../../presentation/). 
```cpp
// Создать экземпляр класса Presentation, представляющего файл презентации
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// Клонировать нужный слайд в конец коллекции слайдов той же презентации
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// Клонировать нужный слайд в указанную позицию в той же презентации
slides->InsertClone(2, slides->idx_get(1));
// Сохранить изменённую презентацию на диск
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
 Следующий пример показывает, как клонировать в другую позицию внутри [Presentation](../../presentation/). 
```cpp
// Создать экземпляр класса Presentation для загрузки исходного файла презентации
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// Создать экземпляр класса Presentation для целевого PPTX (где будет клонироваться слайд)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// Сохранить целевую презентацию на диск
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) метод


Вставляет копию указанного слайда в указанную позицию коллекции.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс нового слайда. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) для клонирования. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Макет-слайд для нового слайда. |

### Возвращаемое значение

Вставленный слайд.

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) метод


Вставляет копию указанного исходного слайда в указанную позицию коллекции. Подходящий макет будет выбран автоматически из указанного мастера (подходящий макет — это макет с тем же типом или именем, что и макет исходного слайда). Если подходящий макет отсутствует, то макет исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout равно false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс нового слайда. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) для клонирования. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Мастер-слайд для нового слайда. |
| allowCloneMissingLayout | **bool** | Если в указанном мастере нет подходящего макета, то макет исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout равно false). |

### Возвращаемое значение

Вставленный слайд.

## См. также

* Тип определения [SharedPtr](../../../system/sharedptr/)
* Класс [ISlide](../../islide/)
* Класс [SlideCollection](../)
* Класс [ILayoutSlide](../../ilayoutslide/)
* Класс [IMasterSlide](../../imasterslide/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)