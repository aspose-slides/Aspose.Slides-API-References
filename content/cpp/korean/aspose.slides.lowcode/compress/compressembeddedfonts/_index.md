---
title: CompressEmbeddedFonts()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 임베디드 폰트에서 사용되지 않는 문자를 제거하여 프레젠테이션을 압축합니다.
type: docs
weight: 27
url: /ko/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) 메서드


[Presentation](../../../aspose.slides/presentation/)를 임베디드 폰트에서 사용되지 않은 문자를 제거함으로써 압축합니다.

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 프레젠테이션 인스턴스 |
## 비고




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Presentation](../../../aspose.slides/presentation/)
* 클래스 [Compress](../)
* 네임스페이스 [Aspose::Slides::LowCode](../../)
* 라이브러리 [Aspose.Slides](../../../)