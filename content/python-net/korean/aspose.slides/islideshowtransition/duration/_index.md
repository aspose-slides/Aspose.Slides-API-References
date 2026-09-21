---
title: duration property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/islideshowtransition/duration/
weight: 40
---
## 기간 속성
슬라이드 전환 효과의 지속 시간을 밀리초 단위로 가져오거나 설정합니다.
읽기/쓰기 **int**.

### 참고

`p14:dur` 속성은 PresentationML 스키마의 `p:transition` 요소와 대응합니다.
설정되지 않은 경우, 지속 시간은 [`ISlideShowTransition.speed`](/slides/python-net/ko/aspose.slides/islideshowtransition/speed) 속성과 전환 유형을 기반으로 자동으로 결정됩니다.

### 정의:
```python
@property
def duration(self):
    ...

@duration.setter
def duration(self, value):
    ...
```

### 관련 항목
* 클래스 [`ISlideShowTransition`](/slides/python-net/ko/aspose.slides/islideshowtransition)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)