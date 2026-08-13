---
title: Equals()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 두 IBaseSlide 인스턴스가 동일한지 판단합니다. 반환 값은 슬라이드의 구조와 정적 콘텐츠를 기반으로 계산됩니다. 모든 도형, 스타일, 텍스트, 애니메이션 및 기타 설정 등이 동일하면 두 슬라이드는 동일합니다. 비교 시 고유 식별자 값(예: SlideId) 및 동적 콘텐츠(예: 날짜 자리표시자의 현재 날짜 값)는 고려되지 않습니다.
type: docs
weight: 183
url: /ko/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) 메서드


두 [IBaseSlide](../) 인스턴스가 같은지 판단합니다. 반환값은 슬라이드 구조와 정적 콘텐츠를 기준으로 계산됩니다. 모든 도형, 스타일, 텍스트, 애니메이션 및 기타 설정 등이 동일할 경우 두 슬라이드는 동일합니다. 비교 시 고유 식별자 값(예: SlideId) 및 동적 콘텐츠(예: Date [Placeholder](../../placeholder/)의 현재 날짜 값)는 고려되지 않습니다.

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | 현재 [IBaseSlide](../)와 비교할 [IBaseSlide](../). |

### 반환 값

**true**가 지정된 [IBaseSlide](../)가 현재 [IBaseSlide](../)와 동일한 경우이며, 그렇지 않으면 **false**.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IBaseSlide](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)