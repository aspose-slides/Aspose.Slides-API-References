---
title: GetAllTextFrames()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает все текстовые кадры в презентации PPTX.
type: docs
weight: 79
url: /ru/aspose.slides.util/slideutil/getalltextframes/
---
## SlideUtil::GetAllTextFrames(System::SharedPtr\<IPresentation\>, bool) метод


Возвращает все текстовые кадры в презентации PPTX.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetAllTextFrames(System::SharedPtr<IPresentation> pres, bool withMasters)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Сканируемая презентация. |
| withMasters | **bool** | Определяет, следует ли сканировать мастер-слайды. |

### Возвращаемое значение

Массив объектов [TextFrame](../../../aspose.slides/textframe/).

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ITextFrame](../../../aspose.slides/itextframe/)
* Класс [IPresentation](../../../aspose.slides/ipresentation/)
* Класс [SlideUtil](../)
* Пространство имён [Aspose::Slides::Util](../../)
* Библиотека [Aspose.Slides](../../../)