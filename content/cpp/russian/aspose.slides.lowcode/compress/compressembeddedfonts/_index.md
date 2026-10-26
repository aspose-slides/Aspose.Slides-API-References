---
title: CompressEmbeddedFonts()
second_title: Справочник API Aspose.Slides для C++
description: Выполняет сжатие презентации, удаляя неиспользуемые символы из встроенных шрифтов.
type: docs
weight: 27
url: /ru/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) метод


Выполняет сжатие [Presentation](../../../aspose.slides/presentation/) путем удаления неиспользуемых символов из встроенных шрифтов.

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Экземпляр презентации |
## Примечания




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Presentation](../../../aspose.slides/presentation/)
* Класс [Compress](../)
* Пространство имен [Aspose::Slides::LowCode](../../)
* Библиотека [Aspose.Slides](../../../)