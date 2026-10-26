---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
지정된 슬라이드의 복사본을 컬렉션 끝에 추가합니다.

### 반환

새 슬라이드.



```python
def add_clone(self, source_slide):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | Slide 복제. |

### 비고

다른 프레젠테이션 간에 슬라이드를 복제할 때 슬라이드의 마스터도 복제될 수 있습니다.
            내부 레지스트리는 자동으로 복제된 마스터를 추적하여 동일한 마스터 슬라이드의 복제본이 여러 개 생성되는 것을 방지하는 데 사용됩니다.
            마스터 슬라이드의 수동 복제는 방지되지 않으며 등록되지도 않습니다.
            복제 프로세스에 대한 더 많은 제어가 필요한 경우 다음을 사용하십시오
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** 또는
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** 슬라이드 복제를 위해,
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** 또는
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** 레이아웃 복제를 위해,
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** 마스터 복제를 위해.


## add_clone(self, source_slide, section) {#islide-isection}
지정된 슬라이드의 복사본을 지정된 섹션 끝에 추가합니다.

### 반환

새 슬라이드.



```python
def add_clone(self, source_slide, section):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | Slide 복제. |
| section | [`ISection`](/slides/python-net/ko/aspose.slides/isection) | 새 슬라이드용 Section. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
지정된 슬라이드의 복사본을 컬렉션 끝에 추가합니다.

### 반환

새 슬라이드.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | Slide 복제. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide) | Layout slide 새 슬라이드용. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
지정된 소스 슬라이드의 복사본을 컬렉션 끝에 추가합니다.
            지정된 master에서 적절한 레이아웃이 자동으로 선택됩니다(적절한 레이아웃은 소스 슬라이드 레이아웃과 동일한 Type 또는 Name을 가진 레이아웃입니다). 적절한 레이아웃이 없을 경우 레이아웃이 <br/><br/>소스 슬라이드에서 복제됩니다(allowCloneMissingLayout가 true인 경우) 또는 <br/><br/>allowCloneMissingLayout가 false인 경우 PptxEditException이 발생합니다.

### 반환

새 슬라이드.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | Slide 복제. |
| dest_master | [`IMasterSlide`](/slides/python-net/ko/aspose.slides/imasterslide) | Master slide 새 슬라이드용. |
| allow_clone_missing_layout | **bool** | 지정된 master에 적절한 레이아웃이 없을 경우 레이아웃이 <br/><br/>소스 슬라이드에서 복제됩니다(allowCloneMissingLayout가 true인 경우) 또는 <br/><br/>allowCloneMissingLayout가 false인 경우 PptxEditException이 발생합니다. |

### 예외

| 예외 | 설명 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception) | 지정된 master에 적절한 레이아웃이 없고 allowCloneMissingLayout가 false인 경우 발생합니다. |



### 관련 항목
* class [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide)
* class [`IMasterSlide`](/slides/python-net/ko/aspose.slides/imasterslide)
* class [`ISection`](/slides/python-net/ko/aspose.slides/isection)
* class [`ISlide`](/slides/python-net/ko/aspose.slides/islide)
* class [`ISlideCollection`](/slides/python-net/ko/aspose.slides/islidecollection)
* class [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)