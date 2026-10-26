---
title: WriteAsEmf()
second_title: C++용 Aspose.Slides API 레퍼런스
description: SVG 이미지를 EMF 파일로 저장합니다.
type: docs
weight: 53
url: /ko/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) 메서드

SVG 이미지를 EMF 파일로 저장합니다.

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 대상 스트림 |
## 비고

다음 예제는 SVG 이미지를 메타파일로 저장하는 방법을 보여줍니다.
```cpp
// 새 SVG 이미지를 생성합니다
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// SVG 이미지를 메타파일로 저장합니다
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
이 샘플은 SVG 이미지를 메타파일로 프레젠테이션 이미지 컬렉션에 추가하는 방법을 보여줍니다.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// 새로운 SVG 이미지를 생성합니다
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// SVG 이미지를 메타파일로 저장합니다
svgImage->WriteAsEmf(memStream);
// 메타파일을 이미지 컬렉션에 추가합니다
pres->get_Images()->AddImage(memStream->ToArray());
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [ISvgImage](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)