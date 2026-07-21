---
title: Paragraph()
second_title: Справочник API Aspose.Slides для C++
description: "Перебрать каждый ForEach::Paragraph в презентации."
type: docs
weight: 53
url: /ru/aspose.slides.lowcode/foreach/paragraph/
---
## ForEach::Paragraph(System::SharedPtr\<Presentation\>, ForEach::ForEachParagraphCallback) метод

Перебрать каждый [ForEach::Paragraph](./) в [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, ForEach::ForEachParagraphCallback forEachParagraph)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) для перебора абзацев |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | Обратный вызов, который будет вызываться для каждого абзаца |
## Примечания

Фигуры будут перебираться во всех типах слайдов - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) и [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, callback);
```

## ForEach::Paragraph(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachParagraphCallback) метод

Перебрать каждый [ForEach::Paragraph](./) в [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachParagraphCallback forEachParagraph)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) для перебора абзацев |
| includeNotes | **bool** | Флаг, указывающий, следует ли включать NotesSlides в обработку. |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | Обратный вызов, который будет вызываться для каждого абзаца |
## Примечания

Фигуры будут перебираться во всех типах слайдов - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) и [NotesSlide](../../../aspose.slides/notesslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, true, callback);
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Типовое определение [ForEachParagraphCallback](../foreachparagraphcallback/)
* Класс [Presentation](../../../aspose.slides/presentation/)
* Класс [ForEach](../)
* Пространство имён [Aspose::Slides::LowCode](../../)
* Библиотека [Aspose.Slides](../../../)