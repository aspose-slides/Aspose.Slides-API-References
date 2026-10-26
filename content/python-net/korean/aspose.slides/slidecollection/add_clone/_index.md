---
title: add_clone method
second_title: Aspose.Slides Python용 .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/slidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
지정된 슬라이드의 복사본을 컬렉션의 끝에 추가합니다.

### 반환값

새 슬라이드.



```python
def add_clone(self, source_slide):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | 복제할 슬라이드. |

### 비고

다른 프레젠테이션 간에 슬라이드를 복제할 때 슬라이드의 마스터도 복제될 수 있습니다.
내부 레지스트리는 자동으로 복제된 마스터를 추적하여 동일한 마스터 슬라이드의 복제본이 여러 개 생성되는 것을 방지합니다.
마스터 슬라이드의 수동 복제는 방지되거나 등록되지 않습니다.
복제 프로세스를 보다 세밀하게 제어하려면
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** 또는
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** 를 사용하여 슬라이드를 복제하고,
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** 또는
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** 를 사용하여 레이아웃을 복제하고,
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** 를 사용하여 마스터를 복제합니다.


## add_clone(self, source_slide, section) {#islide-isection}
지정된 슬라이드의 복사본을 지정된 섹션의 끝에 추가합니다.

### 반환값

새 슬라이드.



```python
def add_clone(self, source_slide, section):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | 복제할 슬라이드. |
| section | [`ISection`](/slides/python-net/ko/aspose.slides/isection) | 새 슬라이드의 섹션. |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
지정된 슬라이드의 복사본을 컬렉션의 끝에 추가합니다.

### 반환값

새 슬라이드.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | 복제할 슬라이드. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide) | 새 슬라이드의 레이아웃 슬라이드. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
지정된 원본 슬라이드의 복사본을 컬렉션의 끝에 추가합니다.
적절한 레이아웃은 지정된 마스터에서 자동으로 선택됩니다(적절한 레이아웃은 원본 슬라이드의 레이아웃과 동일한 Type 또는 Name을 가진 레이아웃입니다). 적절한 레이아웃이 없을 경우 원본 슬라이드의 레이아웃이 <br/><br/>            복제됩니다(allowCloneMissingLayout가 true인 경우) 또는 <br/><br/>            PptxEditException이 발생합니다(allowCloneMissingLayout가 false인 경우).

### 반환값

새 슬라이드.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | 복제할 슬라이드. |
| dest_master | [`IMasterSlide`](/slides/python-net/ko/aspose.slides/imasterslide) | 새 슬라이드의 마스터 슬라이드. |
| allow_clone_missing_layout | **bool** | 지정된 마스터에 적절한 레이아웃이 없을 경우 원본 슬라이드의 레이아웃이 <br/><br/>            복제됩니다(allowCloneMissingLayout가 true인 경우) 또는 <br/><br/>            PptxEditException이 발생합니다(allowCloneMissingLayout가 false인 경우). |

### 예외

| 예외 | 설명 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception) | 지정된 마스터에 적절한 레이아웃이 없고 <br/>            allowCloneMissingLayout가 false인 경우 발생합니다. |



### 참고
* 클래스 [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide)
* 클래스 [`IMasterSlide`](/slides/python-net/ko/aspose.slides/imasterslide)
* 클래스 [`ISection`](/slides/python-net/ko/aspose.slides/isection)
* 클래스 [`ISlide`](/slides/python-net/ko/aspose.slides/islide)
* 클래스 [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception)
* 클래스 [`SlideCollection`](/slides/python-net/ko/aspose.slides/slidecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)