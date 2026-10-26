---
title: add method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/masterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
새 레이아웃 슬라이드를 컬렉션 끝에 추가합니다.

### Returns

추가된 슬라이드.

```python
def add(self, layout_type, layout_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/ko/aspose.slides/slidelayouttype) | 새 레이아웃의 레이아웃 유형.<br/><br/>            지원되는 레이아웃 유형: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            지금 지원되지 않는 다른 레이아웃 유형: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | 새 레이아웃의 이름. 전달된 이름이 이미 사용 중인 경우 ArgumentException이 발생합니다.<br/><br/>            None 매개변수가 전달되면 전달된 레이아웃 유형에 따라 이름이 자동으로 생성됩니다.<br/><br/>            (예: "Title Slide" 또는 "1_Title Slide", "2_..", 등). |

### Remarks

1) `layout_type`의 값 SlideLayoutType.Custom에 대한 레이아웃이 추가되며, 플레이스홀더와 도형이 없습니다. 2) 이 메서드와 동등한 메서드는 **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** 로, [`IPresentation.layout_slides`](/slides/python-net/ko/aspose.slides/ipresentation/layout_slides) 속성을 통해 접근합니다.

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | 지원되지 않는 `layout_type` 값이 전달된 경우 발생합니다. 지금 지원되지 않는 레이아웃 유형: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | `layout_name` 값이 이미 레이아웃 컬렉션에 사용 중인 경우 발생합니다.<br/>            이 레이아웃 컬렉션에서. |

### See Also
* 클래스 [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide)
* 클래스 [`MasterLayoutSlideCollection`](/slides/python-net/ko/aspose.slides/masterlayoutslidecollection)
* 열거형 [`SlideLayoutType`](/slides/python-net/ko/aspose.slides/slidelayouttype)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)