---
title: GetPresentationText()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 슬라이드에서 원시 텍스트를 검색합니다
type: docs
weight: 40
url: /ko/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) method

슬라이드에서 원시 텍스트를 검색합니다

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 입력 파일 |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 추출 모드 |

### 반환 값

원시 슬라이드 텍스트를 나타내는 SlideText 배열을 포함하는 [PresentationText](../../presentationtext/) 인스턴스

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) method

슬라이드에서 원시 텍스트를 검색합니다

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 입력 스트림 |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 추출 모드 |

### 반환 값

원시 슬라이드 텍스트를 나타내는 SlideText 배열을 포함하는 [PresentationText](../../presentationtext/) 인스턴스

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) method

슬라이드에서 원시 텍스트를 검색합니다

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 입력 스트림 |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 추출 모드 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 로드 옵션 |

### 반환 값

원시 슬라이드 텍스트를 나타내는 SlideText 배열을 포함하는 [PresentationText](../../presentationtext/) 인스턴스

## 참고

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationText](../../ipresentationtext/)
* Class [String](../../../system/string/)
* Class [IPresentationFactory](../)
* Class [Stream](../../../system.io/stream/)
* Class [ILoadOptions](../../iloadoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)