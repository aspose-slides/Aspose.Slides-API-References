---
title: Hyperlink constructor
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
하이퍼링크의 인스턴스를 생성합니다.


```python
def __init__(self, url):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| url | **str** | 하이퍼링크 URL. |


## __init__(self, slide) {#islide}
특정 슬라이드를 가리키는 하이퍼링크 인스턴스를 생성합니다.
참고: 생성된 하이퍼링크는 동일 프레젠테이션의 객체에 할당되어야 하며, 그렇지 않으면 링크가 NoAction으로 저장됩니다.


```python
def __init__(self, slide):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | 대상 슬라이드. |


## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
다른 하이퍼링크를 소스로 사용하여 보조 속성을 재정의하면서 하이퍼링크 인스턴스를 생성합니다.


```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/ko/aspose.slides/hyperlink) | 원본 하이퍼링크 |
| target_frame | **str** | 대상 프레임 |
| tooltip | **str** | 툴팁 텍스트 |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |



### 참조
* 클래스 [`Hyperlink`](/slides/python-net/ko/aspose.slides/hyperlink)
* 클래스 [`ISlide`](/slides/python-net/ko/aspose.slides/islide)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)