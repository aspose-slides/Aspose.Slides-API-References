---
title: AddClone()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 레이아웃 슬라이드의 복사본을 컬렉션의 끝에 추가합니다.
type: docs
weight: 1
url: /ko/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) 메서드

지정된 레이아웃 슬라이드의 복사본을 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 복제할. |

### 반환 값

추가된 슬라이드.

## 비고

1) 새로운 레이아웃은 이 레이아웃 슬라이드 컬렉션의 상위 마스터 슬라이드와 연결됩니다. 따라서 이것은 PowerPoint에서 "Use Destination Theme" 옵션을 사용한 복사/붙여넣기와 동일합니다. 2) 이 메서드와 동일한 방법은 [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) 메서드이며, [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) 속성을 통해 액세스합니다. 

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ILayoutSlide](../../ilayoutslide/)
* 클래스 [MasterLayoutSlideCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)