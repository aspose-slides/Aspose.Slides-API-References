---
title: InsertClone()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다.
type: docs
weight: 27
url: /ko/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) 메서드

지정된 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 새 슬라이드의 인덱스. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/)을 복제합니다. |

### 반환 값

삽입된 슬라이드.

## 비고

다른 프레젠테이션 간에 슬라이드를 복제할 때 슬라이드의 마스터도 복제될 수 있습니다. 내부 레지스트리는 자동으로 복제된 마스터를 추적하여 동일한 마스터 슬라이드의 복제본이 여러 개 생성되는 것을 방지합니다. 마스터 슬라이드의 수동 복제는 방지되거나 등록되지 않습니다. 복제 프로세스를 더 세부적으로 제어하려면 슬라이드 복제에 [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) 또는 [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./)을 사용하고 마스터 복제에 [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/)를 사용하십시오.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) 메서드

지정된 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 새 슬라이드의 인덱스. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/)을 복제합니다. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | 새 슬라이드에 대한 레이아웃 슬라이드. |

### 반환 값

삽입된 슬라이드.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) 메서드

지정된 소스 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. 지정된 마스터에서 적절한 레이아웃이 자동으로 선택됩니다(적절한 레이아웃은 소스 슬라이드의 레이아웃과 동일한 Type 또는 Name을 가진 레이아웃입니다). 적절한 레이아웃이 없을 경우, 소스 슬라이드의 레이아웃이 복제됩니다(allowCloneMissingLayout가 true인 경우) 또는 PptxEditException이 발생합니다(allowCloneMissingLayout가 false인 경우).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 새 슬라이드의 인덱스. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/)을 복제합니다. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 새 슬라이드에 대한 마스터 슬라이드. |
| allowCloneMissingLayout | **bool** | 지정된 마스터에 적절한 레이아웃이 없을 경우, 소스 슬라이드의 레이아웃이 복제됩니다(allowCloneMissingLayout가 true인 경우) 또는 PptxEditException이 발생합니다(allowCloneMissingLayout가 false인 경우). |

### 반환 값

삽입된 슬라이드.

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISlide](../../islide/)
* 클래스 [ISlideCollection](../)
* 클래스 [ILayoutSlide](../../ilayoutslide/)
* 클래스 [IMasterSlide](../../imasterslide/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)