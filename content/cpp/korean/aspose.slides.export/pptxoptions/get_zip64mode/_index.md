---
title: get_Zip64Mode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "Presentation 문서에 ZIP64 형식이 사용되는지 여부를 지정합니다. 기본값은 Zip64Mode::IfNecessary입니다."
type: docs
weight: 27
url: /ko/aspose.slides.export/pptxoptions/get_zip64mode/
---
## PptxOptions::get_Zip64Mode() 메서드

ZIP64 형식이 [Presentation](../../../aspose.slides/presentation/) 문서에 사용되는지 여부를 지정합니다. 기본값은 [Zip64Mode::IfNecessary](../../zip64mode/)입니다.

```cpp
Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::PptxOptions::get_Zip64Mode() override
```

## 비고

예제:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## 참조

* Enum [Zip64Mode](../../zip64mode/)
* Class [PptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)