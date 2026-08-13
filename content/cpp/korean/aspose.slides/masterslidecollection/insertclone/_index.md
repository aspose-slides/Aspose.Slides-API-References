---
title: InsertClone()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 마스터 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. 연결된 레이아웃 슬라이드도 복사됩니다.
type: docs
weight: 105
url: /ko/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) 메서드


지정된 마스터 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. 연결된 레이아웃 슬라이드도 복사됩니다.

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 새 슬라이드의 인덱스. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) 복제용. |

### 반환 값

삽입된 마스터 슬라이드.

## 비고



다음 예제는 다른 PowerPoint [Presentation](../../presentation/)에서 마스터 슬라이드를 복제하는 방법을 보여줍니다.
```cpp
// 소스 프레젠테이션 파일을 로드하기 위해 Presentation 클래스를 인스턴스화합니다
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// 슬라이드가 복제될 대상 프레젠테이션을 위해 Presentation 클래스를 인스턴스화합니다
auto destPres = System::MakeObject<Presentation>();

// 소스 프레젠테이션의 슬라이드 컬렉션에서 ISlide를 인스턴스화하고
// 마스터 슬라이드
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// 대상 프레젠테이션의 마스터 슬라이드를 가져옵니다
auto masters = destPres->get_Masters();
// 원하는 마스터 슬라이드를 소스 프레젠테이션에서 마스터 컬렉션으로 복제합니다
// 대상 프레젠테이션
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// 대상 프레젠테이션의 슬라이드 컬렉션
auto slides = destPres->get_Slides();
// 소스 슬라이드를 대상 슬라이드 컬렉션에 복제합니다.
slides->AddClone(sourceSlide, iSlide, true);
// 대상 프레젠테이션을 디스크에 저장합니다
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## 참조

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMasterSlide](../../imasterslide/)
* 클래스 [MasterSlideCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)