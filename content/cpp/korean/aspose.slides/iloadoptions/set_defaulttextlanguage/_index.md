---
title: set_DefaultTextLanguage()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "프레젠테이션 텍스트의 기본 언어를 설정합니다. System::String을 작성하십시오."
type: docs
weight: 326
url: /ko/aspose.slides/iloadoptions/set_defaulttextlanguage/
---
## ILoadOptions::set_DefaultTextLanguage(System::String) 메서드

프레젠테이션 텍스트의 기본 언어를 설정합니다. [System::String](../../../system/string/)를 작성하십시오.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DefaultTextLanguage(System::String value)=0
```

## 비고

예:
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

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [ILoadOptions](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)