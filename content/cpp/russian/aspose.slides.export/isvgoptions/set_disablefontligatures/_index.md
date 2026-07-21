---
title: set_DisableFontLigatures()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает значение, указывающее, следует ли рендерить текст без использования лигатур. При установке в true лигатуры будут отключены в выводе. По умолчанию это свойство имеет значение false.
type: docs
weight: 339
url: /ru/aspose.slides.export/isvgoptions/set_disablefontligatures/
---
## ISVGOptions::set_DisableFontLigatures(bool) метод

Sets a value indicating whether text is rendered without using ligatures. When set to **true**, ligatures will be disabled in the rendered output. By default, this property is set to **false**.

```cpp
virtual void Aspose::Slides::Export::ISVGOptions::set_DisableFontLigatures(bool value)=0
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
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)