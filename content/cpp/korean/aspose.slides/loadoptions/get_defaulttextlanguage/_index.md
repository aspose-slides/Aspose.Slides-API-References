---
title: get_DefaultTextLanguage()
second_title: Aspose.Slides for C++ API 참조
description: "프레젠테이션 텍스트에 대한 기본 언어를 반환합니다. System::String을 읽으십시오."
type: docs
weight: 313
url: /ko/aspose.slides/loadoptions/get_defaulttextlanguage/
---
## LoadOptions::get_DefaultTextLanguage() 메서드


프레젠테이션 텍스트에 대한 기본 언어를 반환합니다. [System::String](../../../system/string/)를 읽으십시오.

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultTextLanguage() override
```

## 비고


예시: 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DefaultTextLanguage(u"en-US");

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(loadOptions);

// Add new rectangle shape with text
System::SharedPtr<IAutoShape> shp = pres->get_Slide(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 50.0f, 50.0f, 150.0f, 50.0f);
shp->get_TextFrame()->set_Text(u"New Text");

// Check the first portion language
System::SharedPtr<IPortion> portion = shp->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
System::Console::WriteLine(portion->get_PortionFormat()->get_LanguageId());
```

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [LoadOptions](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)