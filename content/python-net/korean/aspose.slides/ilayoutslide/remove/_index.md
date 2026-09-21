---
title: remove method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ilayoutslide/remove/
weight: 60
---
## remove(self) {#}
프레젠테이션에서 레이아웃을 제거합니다.


```python
def remove(self):
    ...
```


### 비고

PptxEditException이 발생하는 것을 방지하려면 레이웃의 HasDependingSlides 속성을 먼저 확인하십시오.

### 예외

| 예외 | 설명 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception) | 프레젠테이션에서 레이아웃이 이미 제거되었거나 프레젠테이션에서 레이아웃이 사용 중인 경우(HasDependingSlides 속성이 true인 경우) 발생합니다. |



### 참고
* 클래스 [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide)
* 클래스 [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)