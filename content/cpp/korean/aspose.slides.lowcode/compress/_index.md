---
title: Compress
second_title: C++용 Aspose.Slides API 참조
description: Presentation을 압축하기 위한 메서드 그룹을 나타냅니다.
type: docs
weight: 14
url: /ko/aspose.slides.lowcode/compress/
---
## 압축 클래스

압축 [Presentation](../../aspose.slides/presentation/)을(를) 위한 메서드 그룹을 나타냅니다.

```cpp
class Compress
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | 임베디드 폰트에서 사용되지 않은 문자를 제거하여 [Presentation](../../aspose.slides/presentation/)를 압축합니다. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | 사용되지 않은 레이아웃 슬라이드를 제거하여 [Presentation](../../aspose.slides/presentation/)를 압축합니다. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | 사용되지 않은 마스터 슬라이드를 제거하여 [Presentation](../../aspose.slides/presentation/)를 압축합니다. |
## 비고

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 참고

* 네임스페이스 [Aspose::Slides::LowCode](../)
* 라이브러리 [Aspose.Slides](../../)