---
title: RemoveUnusedLayoutSlides()
second_title: Aspose.Slides для C++ справка по API
description: Выполняет сжатие Presentation за счёт удаления неиспользуемых макетных слайдов.
type: docs
weight: 14
url: /ru/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---
## Compress::RemoveUnusedLayoutSlides(System::SharedPtr\<Presentation\>) метод

Выполняет сжатие [Presentation](../../../aspose.slides/presentation/) путем удаления неиспользуемых макетных слайдов.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedLayoutSlides(System::SharedPtr<Presentation> pres)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Экземпляр презентации |
## Примечания




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedLayoutSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Presentation](../../../aspose.slides/presentation/)
* Класс [Compress](../)
* Пространство имён [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)