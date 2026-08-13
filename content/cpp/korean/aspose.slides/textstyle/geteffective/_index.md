---
title: GetEffective()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 상속이 적용된 효과적인 텍스트 스타일 서식 데이터를 가져옵니다.
type: docs
weight: 27
url: /ko/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() 메서드


상속이 적용된 효과적인 텍스트 스타일 서식 데이터를 가져옵니다.

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```


### 반환값

A [ITextStyleEffectiveData](../../itextstyleeffectivedata/).
## 비고


이 예제는 효과적인 텍스트 스타일 속성 중 일부를 가져오는 방법을 보여줍니다. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextStyle = shape->get_TextFrame()->get_TextFrameFormat()->get_TextStyle()->GetEffective();

for (int32_t i = 0; i <= 8; i++)
{
    auto effectiveStyleLevel = effectiveTextStyle->GetLevel(i);
    Console::WriteLine(String(u"= Effective paragraph formatting for style level #") + i + u" =");

    Console::WriteLine(String(u"Depth: ") + effectiveStyleLevel->get_Depth());
    Console::WriteLine(String(u"Indent: ") + effectiveStyleLevel->get_Indent());
    Console::WriteLine(String(u"Alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_Alignment()));
    Console::WriteLine(String(u"Font alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_FontAlignment()));
}
```

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* 클래스 [TextStyle](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)