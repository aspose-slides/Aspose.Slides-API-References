---
title: Equals()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 두 IBaseSlide 인스턴스가 동일한지 여부를 결정합니다. 반환 값은 슬라이드의 구조와 정적 콘텐츠를 기반으로 계산됩니다. 모든 도형, 스타일, 텍스트, 애니메이션 및 기타 설정 등이 동일하면 두 슬라이드는 동일합니다. 비교에서는 고유 식별자 값(e.g. SlideId) 및 동적 콘텐츠(e.g. 현재 날짜 값 in Date Placeholder)를 고려하지 않습니다.
type: docs
weight: 170
url: /ko/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) method

두 [IBaseSlide](../../ibaseslide/) 인스턴스가 동일한지 여부를 확인합니다. 반환 값은 슬라이드의 구조와 정적 콘텐츠를 기반으로 계산됩니다. 모든 도형, 스타일, 텍스트, 애니메이션 및 기타 설정 등이 동일하면 두 슬라이드는 동일합니다. 등. 비교 시 고유 식별자 값(e.g. SlideId) 및 동적 콘텐츠(e.g. 현재 날짜값 in Date [Placeholder](../../placeholder/))는 고려되지 않습니다.

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | 현재 [IBaseSlide](../../ibaseslide/)와 비교할 [IBaseSlide](../../ibaseslide/). |

### 반환 값

**true**가 지정된 [IBaseSlide](../../ibaseslide/)가 현재 [IBaseSlide](../../ibaseslide/)와 동일한 경우; 그렇지 않으면 **false**.

## 비고

다음 예제는 두 슬라이드를 비교하는 방법을 보여줍니다. 
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IBaseSlide](../../ibaseslide/)
* 클래스 [BaseSlide](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)