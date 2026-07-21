---
title: set_DisableFontLigatures()
second_title: Aspose.Slides для C++ справка API
description: Устанавливает значение, указывающее, следует ли рендерить текст без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию это свойство имеет значение false.
type: docs
weight: 53
url: /ru/aspose.slides.export/irenderingoptions/set_disablefontligatures/
---
## IRenderingOptions::set_DisableFontLigatures(bool) метод


Устанавливает значение, указывающее, следует ли рендерить текст без использования лигатур. При установке в **true** лигатуры будут отключены в выводе. По умолчанию это свойство имеет значение **false**.

```cpp
virtual void Aspose::Slides::Export::IRenderingOptions::set_DisableFontLigatures(bool value)=0
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

* Класс [IRenderingOptions](../)
* Пространство имен [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)