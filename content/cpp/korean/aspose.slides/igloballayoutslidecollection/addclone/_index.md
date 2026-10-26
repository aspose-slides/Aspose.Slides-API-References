---
title: AddClone()
second_title: Aspose.Slides C++ API 레퍼런스
description: 지정된 레이아웃 슬라이드의 복사본을 프레젠테이션에 추가합니다.
type: docs
weight: 1
url: /ko/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) 메서드

지정된 레이아웃 슬라이드의 복사본을 프레젠테이션에 추가합니다.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 복제할 대상. |

### 반환 값

추가된 슬라이드.

## 참고

다른 프레젠테이션 간에 레이아웃을 복제할 때 레이아웃의 마스터도 복제될 수 있어 원본 서식을 유지합니다. 내부 레지스트리를 사용하여 자동으로 복제된 마스터를 추적하고 동일한 마스터 슬라이드의 복제본이 여러 개 생성되는 것을 방지합니다. 마스터 슬라이드의 수동 복제는 방지되지 않으며 등록되지도 않습니다.

## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) 메서드

지정된 레이아웃 슬라이드의 복사본을 프레젠테이션에 추가합니다.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 복제할 대상. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 새 레이아웃을 위한 마스터 슬라이드. |

### 반환 값

추가된 슬라이드.

## 참고

새 레이아웃은 대상 프레젠테이션에 정의된 마스터와 연결됩니다. 따라서 이는 PowerPoint에서 "Use Destination Theme" 옵션을 사용한 복사/붙여넣기와 동일합니다.

## 참고 항목

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ILayoutSlide](../../ilayoutslide/)
* 클래스 [IGlobalLayoutSlideCollection](../)
* 클래스 [IMasterSlide](../../imasterslide/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)