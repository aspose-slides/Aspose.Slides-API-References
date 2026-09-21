---
title: add method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/igloballayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
프레젠테이션에 새 레이아웃 슬라이드를 추가합니다.

### 반환

추가된 슬라이드.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/ko/aspose.slides/imasterslide) | 새 레이아웃에 대한 마스터 슬라이드. |
| layout_type | [`SlideLayoutType`](/slides/python-net/ko/aspose.slides/slidelayouttype) | 새 레이아웃의 레이아웃 유형.<br/><br/>            지원되는 레이아웃 유형: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            현재 지원되지 않는 레이아웃 유형: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | 새 레이아웃의 이름. 전달된 이름이 이미 사용 중이면 ArgumentException이 발생합니다.<br/><br/>            None 매개변수가 전달되면 레이아웃 유형에 따라 자동으로 이름이 생성됩니다.<br/><br/>            (예: "Title Slide" 또는 "1_Title Slide", "2_..", 등). |

### 비고

1) `layout_type`의 값 SlideLayoutType.Custom에 대한 추가된 레이아웃은 자리 표시자와 도형이 없습니다.  
2) 이 메서드와 유사한 메서드는 **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** [`IMasterSlide.layout_slides`](/slides/python-net/ko/aspose.slides/imasterslide/layout_slides) 속성을 통해 접근합니다.

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | 지원되지 않는 `layout_type` 매개변수 값이 전달될 경우 발생합니다. 현재 지원되지 않는 레이아웃 유형: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | `master`가 None인 경우 발생합니다. |
| **RuntimeError(Proxy error(ArgumentException))** | `master`가 다른 프레젠테이션에 속한 경우 발생합니다. |
| **RuntimeError(Proxy error(ArgumentException))** | `layout_name` 값이 `master`의 레이아웃 콜렉션에 이미 사용 중인 경우 발생합니다. <br/>            |

### 또한 보기
* 클래스 [`IGlobalLayoutSlideCollection`](/slides/python-net/ko/aspose.slides/igloballayoutslidecollection)
* 클래스 [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide)
* 클래스 [`IMasterSlide`](/slides/python-net/ko/aspose.slides/imasterslide)
* 열거형 [`SlideLayoutType`](/slides/python-net/ko/aspose.slides/slidelayouttype)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)