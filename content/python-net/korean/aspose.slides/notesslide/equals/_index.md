---
title: equals method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/notesslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
두 IBaseSlide 인스턴스가 같은지 여부를 결정합니다.
            반환값은 슬라이드의 구조와 정적 콘텐츠를 기반으로 계산됩니다.
            모든 도형, 스타일, 텍스트, 애니메이션 및 기타 설정 등이 동일하면 두 슬라이드는 동일합니다. 비교에서는 고유 식별자 값(예: SlideId)과 동적 콘텐츠(예: 날짜 자리표시자에 현재 날짜 값)는 고려되지 않습니다.

### 반환

**true**  지정된 IBaseSlide가 현재 IBaseSlide와 동일하면; 
            그렇지 않으면, **false** .

```python
def equals(self, slide):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide) | 현재 IBaseSlide와 비교할 IBaseSlide. |

### 참조
* 클래스 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide)
* 클래스 [`NotesSlide`](/slides/python-net/ko/aspose.slides/notesslide)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)