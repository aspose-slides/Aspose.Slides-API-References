---
title: find_shape method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.util/slideutil/find_shape/
weight: 30
---
## find_shape(pres, alt_text) {#ipresentation-str}
PPTX 프레젠테이션에서 대체 텍스트로 도형을 찾습니다.

### 반환값

Shape or None.



```python
@staticmethod
def find_shape(pres, alt_text):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pres | [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) | 스캔된 프레젠테이션. |
| alt_text | **str** | 도형의 대체 텍스트. |


## find_shape(slide, alt_text) {#ibaseslide-str}
PPTX 프레젠테이션의 슬라이드에서 대체 텍스트로 도형을 찾습니다.

### 반환값

Shape or None.



```python
@staticmethod
def find_shape(slide, alt_text):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide) | 스캔된 슬라이드. |
| alt_text | **str** | 도형의 대체 텍스트. |



### 참고
* 클래스 [`IBaseSlide`](/slides/python-net/ko/aspose.slides/ibaseslide)
* 클래스 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation)
* 클래스 [`IShape`](/slides/python-net/ko/aspose.slides/ishape)
* 클래스 [`SlideUtil`](/slides/python-net/ko/aspose.slides.util/slideutil)
* 모듈 [`aspose.slides.util`](/slides/python-net/ko/aspose.slides.util)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)