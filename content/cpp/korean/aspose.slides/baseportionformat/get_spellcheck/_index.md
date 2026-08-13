---
title: get_SpellCheck()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 텍스트 부분에 대해 맞춤법 검사 기능이 활성화되어 있는지 여부를 나타내는 값을 가져옵니다. 이 속성이 false로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. true로 설정하면 맞춤법 검사가 허용됩니다. 기본값은 false입니다.
type: docs
weight: 599
url: /ko/aspose.slides/baseportionformat/get_spellcheck/
---
## BasePortionFormat::get_SpellCheck() 메서드

텍스트 부분에 대해 맞춤법 검사 기능이 활성화되어 있는지 여부를 나타내는 값을 가져옵니다. 이 속성이 false로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. true로 설정하면 맞춤법 검사가 허용됩니다. 기본값은 **false**입니다.

```cpp
bool Aspose::Slides::BasePortionFormat::get_SpellCheck() override
```

## 참고

다음 예제는 프레젠테이션을 저장하기 전에 SpellCheck 플래그를 활성화하는 방법을 보여줍니다:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
portion->get_PortionFormat()->set_SpellCheck(true);
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## 관련 항목

* 클래스 [BasePortionFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)