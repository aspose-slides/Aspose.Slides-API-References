---
title: equals method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/masternotesslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
IBaseSlide 인스턴스 두 개가 같은지 판단합니다.
반환 값은 슬라이드의 구조와 정적 콘텐츠를 기반으로 계산됩니다.
두 슬라이드가 동일한 것은 모든 모양, 스타일, 텍스트, 애니메이션 및 기타 설정 등이 모두 동일할 때입니다. 비교에서는 고유 식별자 값(예: SlideId) 및 동적 콘텐츠(예: 날짜 자리표시자의 현재 날짜 값)는 고려되지 않습니다.

### 반환값

**true**  지정된 IBaseSlide가 현재 IBaseSlide와 동일하면; 
            그렇지 않으면 **false** .

```python
def equals(self, slide):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide) | 현재 IBaseSlide와 비교할 IBaseSlide. |

### 참조
* 클래스 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide)
* 클래스 [`MasterNotesSlide`](/slides/python-net/ko/aspose.slides/masternotesslide)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)