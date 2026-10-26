---
title: get_Zip64Mode()
second_title: Aspose.Slides для C++ справочника API
description: "Указывает, используется ли формат ZIP64 для документа Presentation. Значение по умолчанию — Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /ru/aspose.slides.export/ipptxoptions/get_zip64mode/
---
## IPptxOptions::get_Zip64Mode() метод

Указывает, используется ли формат ZIP64 для документа [Presentation](../../../aspose.slides/presentation/). Значение по умолчанию — [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::IPptxOptions::get_Zip64Mode()=0
```

## Примечания

Пример:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## См. также

* Перечисление [Zip64Mode](../../zip64mode/)
* Класс [IPptxOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)