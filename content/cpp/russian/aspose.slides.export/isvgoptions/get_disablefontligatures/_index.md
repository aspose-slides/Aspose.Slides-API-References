---
title: get_DisableFontLigatures()
second_title: Справка API Aspose.Slides для C++
description: Получает значение, указывающее, отображается ли текст без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию это свойство имеет значение false.
type: docs
weight: 326
url: /ru/aspose.slides.export/isvgoptions/get_disablefontligatures/
---
## ISSVGOptions::get_DisableFontLigatures() метод


Получает значение, указывающее, отображается ли текст без использования лигатур. При установке в **true** лигатуры будут отключены в выводе. По умолчанию это свойство имеет значение **false**.

```cpp
virtual bool Aspose::Slides::Export::ISVGOptions::get_DisableFontLigatures()=0
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Отключить лигатуры при рендеринге текста

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## См. также

* Класс [ISVGOptions](../)
* Пространство имен [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)