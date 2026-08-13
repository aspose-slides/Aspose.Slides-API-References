---
title: get_Sound()
second_title: Aspose.Slides for C++ API 참조
description: 하이퍼링크의 재생 사운드를 나타냅니다. IAudio를 읽어 보세요.
type: docs
weight: 287
url: /ko/aspose.slides/hyperlink/get_sound/
---
## Hyperlink::get_Sound() 메서드

하이퍼링크의 재생 사운드를 나타냅니다. [IAudio](../../iaudio/)를 읽어 보세요.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Hyperlink::get_Sound() override
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

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAudio](../../iaudio/)
* 클래스 [Hyperlink](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)