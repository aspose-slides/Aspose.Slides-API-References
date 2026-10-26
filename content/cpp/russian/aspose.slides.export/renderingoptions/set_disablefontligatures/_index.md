---
title: set_DisableFontLigatures()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает значение, указывающее, будет ли текст отображаться без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию это свойство установлено в false.
type: docs
weight: 53
url: /ru/aspose.slides.export/renderingoptions/set_disablefontligatures/
---
## RenderingOptions::set_DisableFontLigatures(bool) метод

Устанавливает значение, указывающее, будет ли текст отображаться без использования лигатур. При установке в **true** лигатуры будут отключены в выводе. По умолчанию это свойство установлено в **false**.

```cpp
void Aspose::Slides::Export::RenderingOptions::set_DisableFontLigatures(bool value) override
```

## Примечания

Пример:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Отключить лигатуры при рендеринге текста

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## См. также

* Класс [RenderingOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)