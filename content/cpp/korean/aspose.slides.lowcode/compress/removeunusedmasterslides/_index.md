---
title: RemoveUnusedMasterSlides()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 사용되지 않는 마스터 슬라이드를 제거하여 프레젠테이션을 압축합니다.
type: docs
weight: 1
url: /ko/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) 메서드

사용되지 않는 마스터 슬라이드를 제거하여 [Presentation](../../../aspose.slides/presentation/)의 압축을 수행합니다.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 프레젠테이션 인스턴스 |

## 비고

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 또보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Presentation](../../../aspose.slides/presentation/)
* 클래스 [Compress](../)
* 네임스페이스 [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)