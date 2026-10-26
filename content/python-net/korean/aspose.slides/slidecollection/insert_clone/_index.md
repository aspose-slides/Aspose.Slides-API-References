---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
지정된 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다.

### 반환값
삽입된 슬라이드.

```python
def insert_clone(self, index, source_slide):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 새 슬라이드의 인덱스. |
| source_slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | 복제할 슬라이드. |

### 비고
다른 프레젠테이션 간에 슬라이드를 복제할 때 슬라이드의 마스터도 복제될 수 있습니다.  
내부 레지스트리는 자동으로 복제된 마스터를 추적하여 동일한 마스터 슬라이드의 복제본이 여러 개 생성되는 것을 방지합니다.  
마스터 슬라이드의 수동 복제는 방지되거나 등록되지 않습니다.  
복제 프로세스를 더 제어하려면 다음을 사용하십시오.  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** 또는  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** (슬라이드 복제)와  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** (마스터 복제)를 사용하십시오.

## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
지정된 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다.

### 반환값
삽입된 슬라이드.

```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 새 슬라이드의 인덱스. |
| source_slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | 복제할 슬라이드. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide) | 새 슬라이드에 사용할 레이아웃 슬라이드. |

## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
지정된 소스 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다.  
적절한 레이아웃은 지정된 마스터에서 자동으로 선택됩니다  
(적절한 레이아웃은 소스 슬라이드의 레이아웃과 동일한 Type 또는 Name을 가진 레이아웃입니다). 적절한 레이아웃이 없으면  
소스 슬라이드의 레이아웃이 복제됩니다(allowCloneMissingLayout이 true인 경우) 또는  
PptxEditException이 발생합니다(allowCloneMissingLayout이 false인 경우).

### 반환값
삽입된 슬라이드.

```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 새 슬라이드의 인덱스. |
| source_slide | [`ISlide`](/slides/python-net/ko/aspose.slides/islide) | 복제할 슬라이드. |
| dest_master | [`IMasterSlide`](/slides/python-net/ko/aspose.slides/imasterslide) | 새 슬라이드에 대한 마스터 슬라이드. |
| allow_clone_missing_layout | **bool** | 지정된 마스터에 적절한 레이아웃이 없으면 레이아웃이 <br/><br/>            소스 슬라이드가 복제됩니다(allowCloneMissingLayout이 true인 경우) 또는 <br/><br/>            PptxEditException이 발생합니다(allowCloneMissingLayout이 false인 경우). |

### 예외

| 예외 | 설명 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception) | 지정된 마스터에 적절한 레이아웃이 없고 <br/>            allowCloneMissingLayout이 false인 경우 발생합니다. |

### 참고
* 클래스 [`ILayoutSlide`](/slides/python-net/ko/aspose.slides/ilayoutslide)
* 클래스 [`IMasterSlide`](/slides/python-net/ko/aspose.slides/imasterslide)
* 클래스 [`ISlide`](/slides/python-net/ko/aspose.slides/islide)
* 클래스 [`PptxEditException`](/slides/python-net/ko/aspose.slides/pptxeditexception)
* 클래스 [`SlideCollection`](/slides/python-net/ko/aspose.slides/slidecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)