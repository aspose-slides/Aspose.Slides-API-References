---
title: insert method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/masterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
지정된 위치에 새로운 레이아웃 슬라이드를 삽입합니다.

### 반환값
삽입된 슬라이드.

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | **int** | 새 슬라이드의 인덱스. |
| layout_type | [`SlideLayoutType`](/slides/python-net/ko/aspose.slides/slidelayouttype) | 새 레이아웃의 레이아웃 유형.<br/><br/> 지원되는 레이아웃 유형: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/> 현재 지원되지 않는 레이아웃 유형: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | 새 레이아웃의 이름. 이미 사용 중인 이름이 전달되면 ArgumentException이 발생합니다.<br/><br/> None 매개변수가 전달되면 전달된 레이아웃 유형에 따라 자동으로 이름이 생성됩니다 (예: "Title Slide" 또는 "1_Title Slide", "2_.." 등). |

### 비고
`layout_type`의 SlideLayoutType.Custom 값에 대한 삽입된 레이아웃은 플래이스홀더와 도형이 없습니다.

### 예외
| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | 지원되지 않는 `layout_type` 값이 전달된 경우 발생합니다. 현재 지원되지 않는 레이아웃 유형: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | 레이아웃 이름 `layout_name` 값이 이미 이 레이아웃 컬렉션에 사용 중인 경우 발생합니다. |

### 참조
* 클래스 [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide)
* 클래스 [`MasterLayoutSlideCollection`](/slides/python-net/ko/aspose.slides/masterlayoutslidecollection)
* 열거형 [`SlideLayoutType`](/slides/python-net/ko/aspose.slides/slidelayouttype)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)