---
title: get_Zip64Mode()
second_title: Aspose.Slides для C++ API Reference
description: "Указывает, используется ли формат ZIP64 для документа Presentation. Значение по умолчанию — Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /ru/aspose.slides.export/pptxoptions/get_zip64mode/
---
## PptxOptions::get_Zip64Mode() метод

Указывает, используется ли формат ZIP64 для документа [Presentation](../../../aspose.slides/presentation/). Значение по умолчанию — [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::PptxOptions::get_Zip64Mode() override
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

* Enum [Zip64Mode](../../zip64mode/)
* Класс [PptxOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)