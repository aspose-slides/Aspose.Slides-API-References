---
title: InsertClone()
second_title: Справочник API Aspose.Slides для C++
description: Вставляет копию указанного мастер-слайда в указанную позицию коллекции. Связанные слайды макета также будут скопированы.
type: docs
weight: 105
url: /ru/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) метод

Вставляет копию указанного мастер-слайда в указанную позицию коллекции. Связанные слайды макета также будут скопированы.

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс нового слайда. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) для клонирования. |

### Возвращаемое значение

Вставленный мастер-слайд.

## Замечания

В следующем примере показано, как клонировать мастер-слайд в другой PowerPoint [Presentation](../../presentation/). 
```cpp
// Создать объект класса Presentation для загрузки исходного файла презентации
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// Создать объект класса Presentation для целевой презентации (куда будет клонирован слайд)
auto destPres = System::MakeObject<Presentation>();

// Получить объект ISlide из коллекции слайдов исходной презентации вместе с
// мастер-слайдом
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// Получить мастер-слайды целевой презентации
auto masters = destPres->get_Masters();
// Клонировать нужный мастер-слайд из исходной презентации в коллекцию мастер-слайдов в
// целевой презентации
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// Коллекция слайдов в целевой презентации
auto slides = destPres->get_Slides();
// Клонировать исходный слайд в коллекцию слайдов целевой презентации.
slides->AddClone(sourceSlide, iSlide, true);
// Сохранить целевую презентацию на диск
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IMasterSlide](../../imasterslide/)
* Класс [MasterSlideCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)