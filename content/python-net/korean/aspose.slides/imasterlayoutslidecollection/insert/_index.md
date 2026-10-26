---
title: insert method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
새 레이아웃 슬라이드를 컬렉션의 지정된 위치에 삽입합니다.

### 반환값

삽입된 슬라이드.

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 새 슬라이드의 인덱스. |
| layout_type | [`SlideLayoutType`](/slides/python-net/ko/aspose.slides/slidelayouttype) | 새 레이아웃의 레이아웃 유형입니다.<br/><br/>            지원되는 레이아웃 유형: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            현재 지원되지 않는 레이아웃 유형: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | 새 레이아웃의 이름입니다. 전달된 이름이 이미 사용 중인 경우 ArgumentException이 발생합니다.<br/><br/>            None 파라미터가 전달되면 전달된 레이아웃 유형에 따라 이름이 자동으로 생성됩니다.<br/><br/>            (예: "Title Slide" 또는 "1_Title Slide", "2_.." 등). |

### 비고

`layout_type`의 SlideLayoutType.Custom 값에 대한 삽입된 레이아웃은 플레이스홀더와 쉐이프가 없습니다.

### 예외

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | 지원되지 않는 `layout_type` 매개변수 값이 전달될 경우 발생합니다. 현재 지원되지 않는 레이아웃 유형: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | `layout_name` 값이 이미 레이아웃 컬렉션에 사용 중인 경우 발생합니다.<br/>            이 레이아웃 컬렉션에서. |

### 참조
* 클래스 [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide)
* 클래스 [`IMasterLayoutSlideCollection`](/slides/python-net/ko/aspose.slides/imasterlayoutslidecollection)
* 열거형 [`SlideLayoutType`](/slides/python-net/ko/aspose.slides/slidelayouttype)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)