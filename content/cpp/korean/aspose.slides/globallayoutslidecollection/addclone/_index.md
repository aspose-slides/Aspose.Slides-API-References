---
title: AddClone()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 레이아웃 슬라이드의 복사본을 프레젠테이션에 추가합니다.
type: docs
weight: 1
url: /ko/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) 메서드


지정된 레이아웃 슬라이드의 복사본을 프레젠테이션에 추가합니다.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 복제할. |

### 반환값

Added slide.
## 비고



다른 프레젠테이션 간에 레이아웃을 복제할 때 레이아웃의 마스터도 복제되어 원본 서식을 유지할 수 있습니다. 내부 레지스트리를 사용하여 자동 복제된 마스터를 추적하고 동일한 마스터 슬라이드의 복제본이 여러 개 생성되는 것을 방지합니다. 마스터 슬라이드의 수동 복제는 방지되거나 등록되지 않습니다. 
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) 메서드


지정된 레이아웃 슬라이드의 복사본을 프레젠테이션에 추가합니다.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 복제할. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 새 레이아웃에 대한 마스터 슬라이드. |

### 반환값

Added slide.
## 비고



1) 새 레이아웃은 대상 프레젠테이션에 정의된 마스터와 연결됩니다. 따라서 PowerPoint의 \"Use Destination Theme\" 옵션을 사용한 복사/붙여넣기와 동일합니다. 2) 이 메서드와 동일한 기능은 [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) 메서드이며, [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) 속성을 통해 접근할 수 있습니다. 
## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [GlobalLayoutSlideCollection](../)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)