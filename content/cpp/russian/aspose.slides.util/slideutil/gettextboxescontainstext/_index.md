---
title: GetTextBoxesContainsText()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает все текстовые фреймы на указанном слайде, содержащие заданный текст.
type: docs
weight: 66
url: /ru/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) метод

Возвращает все текстовые фреймы на указанном слайде, содержащие заданный текст.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Слайд для поиска. |
| text | [System::String](../../../system/string/) | Текст для поиска внутри текстовых фреймов. |
| checkPlaceholderText | **bool** | Указывает, следует ли включать текстовые фреймы, которые пусты, но чей заполнительный текст содержит искомый текст. |

### Возвращаемое значение

Массив объектов [ITextFrame](../../../aspose.slides/itextframe/), содержащих указанный текст.

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [ITextFrame](../../../aspose.slides/itextframe/)
* Класс [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Класс [String](../../../system/string/)
* Класс [SlideUtil](../)
* Пространство имен [Aspose::Slides::Util](../../)
* Библиотека [Aspose.Slides](../../../)