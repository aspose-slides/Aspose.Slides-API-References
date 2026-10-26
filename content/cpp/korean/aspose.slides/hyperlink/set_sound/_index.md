---
title: set_Sound()
second_title: C++용 Aspose.Slides API 참조
description: 하이퍼링크의 재생 사운드를 나타냅니다. IAudio를 작성합니다.
type: docs
weight: 300
url: /ko/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) 메서드


하이퍼링크의 재생 사운드를 나타냅니다. [IAudio](../../iaudio/)를 작성합니다.

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 첫 번째 도형 하이퍼링크 가져오기
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // 하이퍼링크 사운드를 바이트 배열로 추출
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## 참조

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAudio](../../iaudio/)
* 클래스 [Hyperlink](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)