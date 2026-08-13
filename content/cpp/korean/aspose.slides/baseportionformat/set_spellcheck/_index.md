---
title: set_SpellCheck()
second_title: Aspose.Slides for C++ API 참조
description: 텍스트 구역에 대해 맞춤법 검사 여부를 나타내는 값을 설정합니다. 이 속성이 false로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. true로 설정하면 맞춤법 검사가 허용됩니다. 기본값은 false입니다.
type: docs
weight: 612
url: /ko/aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) 메서드

텍스트 구역에 대한 맞춤법 검사가 활성화되어 있는지를 나타내는 값을 설정합니다. 이 속성이 false로 설정되면 텍스트 요소에 대한 맞춤법 검사가 억제됩니다. true로 설정하면 맞춤법 검사가 허용됩니다. 기본값은 **false**입니다.

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## 비고

다음 예제는 프레젠테이션을 저장하기 전에 SpellCheck 플래그를 활성화하는 방법을 보여줍니다:
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// 첫 번째 슬라이드의 첫 번째 도형 안에 있는 첫 번째 텍스트 구역에 접근합니다
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// 이 텍스트 구역에 대한 맞춤법 검사를 활성화합니다
portion->get_PortionFormat()->set_SpellCheck(true);
// 수정된 프레젠테이션을 저장합니다
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## 참조

* 클래스 [BasePortionFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)