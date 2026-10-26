---
title: AddClone()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет копию указанного слайда-макета в презентацию.
type: docs
weight: 1
url: /ru/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) метод

Добавляет копию указанного слайда-макета в презентацию.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) для клонирования. |

### Возвращаемое значение

Добавленный слайд.

## Примечания

При клонировании макета между разными презентациями мастер макета также может быть клонирован, чтобы сохранить исходное форматирование. Для отслеживания автоматически клонированных мастеров используется внутренний реестр, что предотвращает создание нескольких копий одного и того же мастер-слайда. Ручное клонирование мастер-слайдов не будет ни предотвращено, ни зарегистрировано.

## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) метод

Добавляет копию указанного слайда-макета в презентацию.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) для клонирования. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Мастер-слайд для нового макета. |

### Возвращаемое значение

Добавленный слайд.

## Примечания

Новый макет будет связан с определённым мастером в целевой презентации. Таким образом, это аналог операции копировать/вставить с опцией \"Use Destination Theme\" в PowerPoint.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ILayoutSlide](../../ilayoutslide/)
* Класс [IGlobalLayoutSlideCollection](../)
* Класс [IMasterSlide](../../imasterslide/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)