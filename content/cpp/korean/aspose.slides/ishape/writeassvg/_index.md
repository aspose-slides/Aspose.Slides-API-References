---
title: WriteAsSvg()
second_title: Aspose.Slides C++ API 레퍼런스
description: Shape의 내용을 SVG 파일로 저장합니다.
type: docs
weight: 560
url: /ko/aspose.slides/ishape/writeassvg/
---
## IShape::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>) 메서드

SVG 파일로 [Shape](../../shape/)의 내용을 저장합니다.

```cpp
virtual void Aspose::Slides::IShape::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 대상 스트림 |

## IShape::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Export::ISVGOptions\>) 메서드

SVG 파일로 [Shape](../../shape/)의 내용을 저장합니다.

```cpp
virtual void Aspose::Slides::IShape::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Export::ISVGOptions> svgOptions)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 대상 스트림 |
| svgOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG 생성 옵션 |

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [IShape](../)
* 클래스 [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)