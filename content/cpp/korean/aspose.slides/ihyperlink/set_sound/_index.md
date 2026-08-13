---
title: set_Sound()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 하이퍼링크의 재생 사운드를 나타냅니다. IAudio를 씁니다.
type: docs
weight: 196
url: /ko/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) 메서드

하이퍼링크의 재생 사운드를 나타냅니다. 쓰기 [IAudio](../../iaudio/).

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
```

## 비고

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 첫 번째 도형 하이퍼링크를 가져옵니다
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // 하이퍼링크 사운드를 바이트 배열로 추출합니다
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAudio](../../iaudio/)
* 클래스 [IHyperlink](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)