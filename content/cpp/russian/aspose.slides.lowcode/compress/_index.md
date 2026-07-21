---
title: Compress
second_title: Aspose.Slides для API справочника C++
description: Представляет группу методов, предназначенных для сжатия Presentation.
type: docs
weight: 14
url: /ru/aspose.slides.lowcode/compress/
---
## Compress класс


Представляет группу методов, предназначенных для сжатия [Presentation](../../aspose.slides/presentation/).

```cpp
class Compress
```

## Методы

| Метод | Описание |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Выполняет сжатие [Presentation](../../aspose.slides/presentation/) путем удаления неиспользуемых символов из встроенных шрифтов. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Выполняет сжатие [Presentation](../../aspose.slides/presentation/) путем удаления неиспользуемых слайдов макета. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Выполняет сжатие [Presentation](../../aspose.slides/presentation/) путем удаления неиспользуемых мастер слайдов. |
## Примечания



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## См. также

* Пространство имён [Aspose::Slides::LowCode](../)
* Библиотека [Aspose.Slides](../../)