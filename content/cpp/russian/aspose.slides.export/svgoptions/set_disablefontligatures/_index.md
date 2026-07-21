---
title: set_DisableFontLigatures()
second_title: Aspose.Slides для C++ API справка
description: Устанавливает значение, указывающее, будет ли текст отрисовываться без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию это свойство имеет значение false.
type: docs
weight: 339
url: /ru/aspose.slides.export/svgoptions/set_disablefontligatures/
---
## SVGOptions::set_DisableFontLigatures(bool) метод

Устанавливает значение, указывающее, будет ли текст отрисовываться без использования лигатур. При установке в **true** лигатуры будут отключены в выводе. По умолчанию это свойство имеет значение **false**.

```cpp
void Aspose::Slides::Export::SVGOptions::set_DisableFontLigatures(bool value) override
```

## Примечания

Пример:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Отключить лигатуры при отображении текста

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## См. также

* Класс [SVGOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)