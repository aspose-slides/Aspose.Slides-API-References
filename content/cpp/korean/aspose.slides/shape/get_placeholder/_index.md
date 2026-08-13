---
title: get_Placeholder()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 도형에 대한 자리 표시자를 반환합니다. 도형에 자리 표시자가 없으면 null을 반환합니다. 읽기 전용 IPlaceholder.
type: docs
weight: 14
url: /ko/aspose.slides/shape/get_placeholder/
---
## Shape::get_Placeholder() 메서드

도형에 대한 자리 표시자를 반환합니다. 도형에 자리 표시자가 없으면 null을 반환합니다. 읽기 전용 [IPlaceholder](../../iplaceholder/).

```cpp
System::SharedPtr<IPlaceholder> Aspose::Slides::Shape::get_Placeholder() override
```

## 비고

다음 예제는 [Placeholder](../../placeholder/)에서 텍스트를 변경하는 방법을 보여줍니다.
```cpp
// Presentation 클래스를 인스턴스화합니다
auto pres = System::MakeObject<Presentation>(u"ReplacingText.pptx");

// 첫 번째 슬라이드에 접근합니다
auto slide = pres->get_Slides()->idx_get(0);

// 플레이스홀더를 찾기 위해 도형들을 반복합니다
for (auto&& shape : slide->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr)
    {
        // 각 플레이스홀더의 텍스트를 변경합니다
        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(u"This is a Placeholder");
    }
}

// 프레젠테이션을 디스크에 저장합니다
pres->Save(u"output_out.pptx", SaveFormat::Pptx);
```
다음 예제는 [Placeholder](../../placeholder/)에 프롬프트 텍스트를 설정하는 방법을 보여줍니다.
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation2.pptx");

auto slide = pres->get_Slides()->idx_get(0);
for (auto&& shape : slide->get_Slide()->get_Shapes())
{
    if (shape->get_Placeholder() != nullptr && System::ObjectExt::Is<AutoShape>(shape))
    {
        System::String text = u"";
        if (shape->get_Placeholder()->get_Type() == PlaceholderType::CenteredTitle)
        {
            text = u"Add Title";
        }
        else if (shape->get_Placeholder()->get_Type() == PlaceholderType::Subtitle)
        {
            text = u"Add Subtitle";
        }

        (System::ExplicitCast<IAutoShape>(shape))->get_TextFrame()->set_Text(text);

        System::Console::WriteLine(System::String::Format(u"Placeholder with text: {0}", text));
    }
}

pres->Save(u"Placeholders_PromptText.pptx", SaveFormat::Pptx);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPlaceholder](../../iplaceholder/)
* 클래스 [Shape](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)