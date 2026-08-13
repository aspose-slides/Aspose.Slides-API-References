---
title: get_Sound()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 하이퍼링크의 재생 사운드를 나타냅니다. IAudio를 읽으세요.
type: docs
weight: 183
url: /ko/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() 메서드

하이퍼링크의 재생 사운드를 나타냅니다. [IAudio](../../iaudio/)을(를) 읽으세요.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
```

## 비고

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 첫 번째 도형 하이퍼링크 가져오기
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // 바이트 배열로 하이퍼링크 사운드 추출
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAudio](../../iaudio/)
* 클래스 [IHyperlink](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)