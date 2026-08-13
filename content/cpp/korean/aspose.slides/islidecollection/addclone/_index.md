---
title: AddClone()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 슬라이드의 복사본을 컬렉션의 끝에 추가합니다.
type: docs
weight: 14
url: /ko/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) 메서드

지정된 슬라이드의 복사본을 컬렉션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 복제. |

### 반환 값

새 슬라이드.

## 비고

다른 프레젠테이션 간에 슬라이드를 복제할 때 슬라이드의 마스터도 복제될 수 있습니다. 내부 레지스트리는 자동으로 복제된 마스터를 추적하여 동일한 마스터 슬라이드의 복제본이 여러 개 생성되는 것을 방지합니다. 마스터 슬라이드의 수동 복제는 방지되지도 않으며 등록되지도 않습니다. 복제 프로세스를 더 제어하려면 슬라이드 복제에 [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) 또는 [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./), 레이아웃 복제에 [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) 또는 [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/), 마스터 복제에 [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/)를 사용하십시오.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) 메서드

지정된 슬라이드의 복사본을 지정된 섹션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 복제. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) 새 슬라이드용. |

### 반환 값

새 슬라이드.

## 비고

```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// 이제 두 번째 섹션에 첫 번째 슬라이드의 복사본이 포함됩니다.
```

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) 메서드

지정된 슬라이드의 복사본을 컬렉션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 복제. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | 새 슬라이드용 레이아웃 슬라이드. |

### 반환 값

새 슬라이드.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) 메서드

지정된 원본 슬라이드의 복사본을 컬렉션의 끝에 추가합니다. 지정된 마스터에서 적절한 레이아웃이 자동으로 선택됩니다(적절한 레이아웃은 원본 슬라이드 레이아웃과 동일한 Type 또는 Name을 가진 레이아웃입니다). 적절한 레이아웃이 없으면 원본 슬라이드의 레이아웃이 복제됩니다(allowCloneMissingLayout가 true인 경우) 또는 PptxEditException이 발생합니다(allowCloneMissingLayout가 false인 경우).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 복제. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | 새 슬라이드용 마스터 슬라이드. |
| allowCloneMissingLayout | **bool** | 지정된 마스터에 적절한 레이아웃이 없으면 원본 슬라이드의 레이아웃이 복제됩니다(allowCloneMissingLayout가 true인 경우) 또는 PptxEditException이 발생합니다(allowCloneMissingLayout가 false인 경우). |

### 반환 값

새 슬라이드.

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ISlide](../../islide/)
* 클래스 [ISlideCollection](../)
* 클래스 [ISection](../../isection/)
* 클래스 [ILayoutSlide](../../ilayoutslide/)
* 클래스 [IMasterSlide](../../imasterslide/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)