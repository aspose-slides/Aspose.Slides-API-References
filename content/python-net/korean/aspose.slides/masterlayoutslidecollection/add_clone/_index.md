---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
지정된 레이아웃 슬라이드의 복사본을 컬렉션 끝에 추가합니다.

### Returns
추가된 슬라이드.

```python
def add_clone(self, source_layout):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide) | 복제할 슬라이드. |

### Remarks
1) 새 레이아웃은 이 레이아웃 슬라이드 컬렉션의 부모 마스터 슬라이드와 연결됩니다. 따라서 PowerPoint에서 "Use Destination Theme" 옵션을 사용한 복사/붙여넣기와 동일합니다.
2) 이 메서드와 유사한 메서드는 **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** 로, [`IPresentation.layout_slides`](/slides/python-net/ko/aspose.slides/ipresentation/layout_slides) 속성을 통해 접근합니다.

### See Also
* 클래스 [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide)
* 클래스 [`MasterLayoutSlideCollection`](/slides/python-net/ko/aspose.slides/masterlayoutslidecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)