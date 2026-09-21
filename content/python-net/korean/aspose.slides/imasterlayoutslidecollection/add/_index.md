---
title: add method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/imasterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
새 레이아웃 슬라이드를 컬렉션의 끝에 추가합니다.

### 반환

추가된 슬라이드.



```python
def add(self, layout_type, layout_name):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/ko/aspose.slides/slidelayouttype) | 새 레이아웃의 레이아웃 유형.<br/><br/>            지원되는 레이아웃 유형: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            현재 지원되지 않는 레이아웃 유형: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | 새 레이아웃의 이름. 전달된 이름이 이미 사용 중이면 ArgumentException이 발생합니다.<br/><br/>            None 매개변수가 전달되면 전달된 레이아웃 유형에 따라 이름이 자동으로 생성됩니다.<br/><br/>            (예: "Title Slide" 또는 "1_Title Slide", "2_..", 등). |

### 비고

1) `layout_type`의 값 SlideLayoutType.Custom에 대한 추가 레이아웃은 플레이스홀더와 도형이 없습니다.
2) 이 메서드와 동일한 기능은 **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** 메서드이며, [`IPresentation.layout_slides`](/slides/python-net/ko/aspose.slides/ipresentation/layout_slides) 속성을 통해 접근합니다.

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | `layout_type` 매개변수에 지원되지 않는 값이 전달될 경우 발생합니다. 현재 지원되지 않는 레이아웃 유형: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | 레이아웃 이름 값 `layout_name`이 이 레이아웃 컬렉션에서 이미 사용 중일 경우 발생합니다. |



### 참고
* 클래스 [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide)
* 클래스 [`IMasterLayoutSlideCollection`](/slides/python-net/ko/aspose.slides/imasterlayoutslidecollection)
* 열거형 [`SlideLayoutType`](/slides/python-net/ko/aspose.slides/slidelayouttype)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)