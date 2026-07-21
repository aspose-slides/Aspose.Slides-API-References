---
title: Portion()
second_title: Справочник API Aspose.Slides для C++
description: "Перебрать каждый ForEach::Portion в презентации."
type: docs
weight: 66
url: /ru/aspose.slides.lowcode/foreach/portion/
---
## ForEach::Portion(System::SharedPtr\<Presentation\>, ForEach::ForEachPortionCallback) метод

Перебрать каждый [ForEach::Portion](./) в [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, ForEach::ForEachPortionCallback forEachPortion)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) для перебора частей |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Обратный вызов, который будет вызываться для каждой части |

## Примечания

Части будут перебраны во всех типах слайдов - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) и [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, callback);
```

## ForEach::Portion(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachPortionCallback) метод

Перебрать каждый [ForEach::Portion](./) в [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachPortionCallback forEachPortion)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) для перебора частей |
| includeNotes | **bool** | Флаг, указывающий, следует ли включать NotesSlides в обработку. |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Обратный вызов, который будет вызываться для каждой части |

## Примечания

Части будут перебраны во всех типах слайдов - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) и [NotesSlide](../../../aspose.slides/notesslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, true, callback);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachPortionCallback](../foreachportioncallback/)
* Класс [Presentation](../../../aspose.slides/presentation/)
* Класс [ForEach](../)
* Пространство имён [Aspose::Slides::LowCode](../../)
* Библиотека [Aspose.Slides](../../../)