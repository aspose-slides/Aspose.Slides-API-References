---
title: get_DisableFontLigatures()
second_title: Aspose.Slides для справки API C++
description: Возвращает значение, указывающее, рендерится ли текст без использования лигатур. При значении true лигатуры будут отключены в выводе. По умолчанию это свойство имеет значение false.
type: docs
weight: 326
url: /ru/aspose.slides.export/svgoptions/get_disablefontligatures/
---
## SVGOptions::get_DisableFontLigatures() метод

Возвращает значение, указывающее, рендерится ли текст без использования лигатур. При значении **true** лигатуры будут отключены в выводе. По умолчанию это свойство имеет значение **false**.

```cpp
bool Aspose::Slides::Export::SVGOptions::get_DisableFontLigatures() override
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

* Класс [SVGOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)