---
title: AddClone()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет копию указанного слайда в конец коллекции.
type: docs
weight: 53
url: /ru/aspose.slides/slidecollection/addclone/
---
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>) метод


Добавляет копию указанного слайда в конец коллекции.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) для клонирования. |

### Возвращаемое значение

Новый слайд.

## Примечания



При клонировании слайда между разными презентациями мастер-слайда также может быть клонирован. Для отслеживания автоматически клонированных мастеров используется внутренний реестр, чтобы предотвратить создание нескольких копий одного и того же мастер-слайда. Ручное клонирование мастер-слайдов не будет ни предотвращено, ни зарегистрировано. Если требуется более тонкий контроль процесса клонирования, используйте [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/addclone/) или [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/addclone/) для клонирования слайдов, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) или [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) для клонирования компоновок и [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) для клонирования мастеров. 
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) метод


Добавляет копию указанного слайда в конец указанного раздела.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) для клонирования. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) для нового слайда. |

### Возвращаемое значение

Новый слайд.

## Примечания



```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// Теперь второй раздел содержит копию первого слайда.
```


## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) метод


Добавляет копию указанного слайда в конец коллекции.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) для клонирования. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Слайд-компоновка для нового слайда. |

### Возвращаемое значение

Новый слайд.

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) метод


Добавляет копию указанного исходного слайда в конец коллекции. Подходящая компоновка будет автоматически выбрана из указанного мастера (подходящая компоновка – это компоновка с тем же типом или именем, что и у исходного слайда). Если подходящая компоновка отсутствует, будет клонирована компоновка исходного слайда (если allowCloneMissingLayout = true) или выброшено исключение PptxEditException (если allowCloneMissingLayout = false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) для клонирования. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Мастер-слайд для нового слайда. |
| allowCloneMissingLayout | **bool** | Если в указанном мастере нет подходящей компоновки, будет клонирована компоновка исходного слайда (если allowCloneMissingLayout = true) или выброшено исключение PptxEditException (если allowCloneMissingLayout = false). |

### Возвращаемое значение

Новый слайд.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISlide](../../islide/)
* Класс [SlideCollection](../)
* Класс [ISection](../../isection/)
* Класс [ILayoutSlide](../../ilayoutslide/)
* Класс [IMasterSlide](../../imasterslide/)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)