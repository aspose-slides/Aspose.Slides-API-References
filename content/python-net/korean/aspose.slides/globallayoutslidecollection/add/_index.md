---
title: add method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/globallayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
프레젠테이션에 새 레이아웃 슬라이드를 추가합니다.

### Returns

Added slide.

```python
def add(self, master, layout_type, layout_name):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/ko/aspose.slides/imasterslide) | 새 레이아웃의 마스터 슬라이드. |
| layout_type | [`SlideLayoutType`](/slides/python-net/ko/aspose.slides/slidelayouttype) | 새 레이아웃의 레이아웃 유형.<br/><br/>            지원되는 레이아웃 유형: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            현재 지원되지 않는 레이아웃 유형: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | 새 레이아웃의 이름. 전달된 이름이 이미 사용 중인 경우 ArgumentException이 발생합니다.<br/><br/>            None 매개변수가 전달되면 전달된 레이웃 유형에 따라 이름이 자동으로 생성됩니다.<br/><br/>            (예: "Title Slide" 또는 "1_Title Slide", "2_..", 등). |

### Remarks

1) `layout_type`의 SlideLayoutType.Custom 값에 대한 추가 레이아웃은 플레이스홀더와 쉐이프가 없습니다.  
2) 이 메서드의 유사 메서드는 **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste**이며 [`IMasterSlide.layout_slides`](/slides/python-net/ko/aspose.slides/imasterslide/layout_slides) 속성을 통해 접근합니다.

### Exceptions

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | 지원되지 않는 `layout_type` 매개변수 값이 전달될 경우 발생합니다. 현재 지원되지 않는 레이아웃 유형: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | `master`가 None인 경우 발생합니다. |
| **RuntimeError(Proxy error(ArgumentException))** | `master`가 다른 프레젠테이션에 속한 경우 발생합니다. |
| **RuntimeError(Proxy error(ArgumentException))** | `layout_name` 값이 `master`의 레이아웃 컬렉션에 이미 사용 중인 경우 발생합니다.<br/>            |

### See Also
* 클래스 [`GlobalLayoutSlideCollection`](/slides/python-net/ko/aspose.slides/globallayoutslidecollection)
* 클래스 [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide)
* 클래스 [`IMasterSlide`](/slides/python-net/ko/aspose.slides/imasterslide)
* 열거형 [`SlideLayoutType`](/slides/python-net/ko/aspose.slides/slidelayouttype)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)