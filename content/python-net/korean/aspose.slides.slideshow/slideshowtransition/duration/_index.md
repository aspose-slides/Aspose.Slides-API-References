---
title: duration property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.slideshow/slideshowtransition/duration/
weight: 40
---
## duration 속성
슬라이드 전환 효과의 duration을 밀리초 단위로 가져오거나 설정합니다.
            읽기/쓰기 **int**.

### 비고

            `p14:dur` 속성은 PresentationML 스키마의 `p:transition` 요소에 해당합니다.
            설정되지 않은 경우, duration은 [`SlideShowTransition.speed`](/slides/python-net/ko/aspose.slides.slideshow/slideshowtransition/speed) 속성을 기반으로 전환 유형에 따라 자동으로 결정됩니다.

### 정의:
```python
@property
def duration(self):
    ...

@duration.setter
def duration(self, value):
    ...
```

### 참고
* 클래스 [`SlideShowTransition`](/slides/python-net/ko/aspose.slides.slideshow/slideshowtransition)
* 모듈 [`aspose.slides.slideshow`](/slides/python-net/ko/aspose.slides.slideshow)
* library [`Aspose.Slides`](/slides/python-net)