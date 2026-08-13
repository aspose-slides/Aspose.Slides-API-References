---
title: GetPresentationText()
second_title: C++용 Aspose.Slides API 참조
description: 슬라이드에서 원시 텍스트를 가져옵니다
type: docs
weight: 53
url: /ko/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) 메서드

슬라이드에서 원시 텍스트를 가져옵니다

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 입력 파일 |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 추출 모드 |

### 반환값

원시 슬라이드 텍스트를 나타내는 SlideText 배열을 포함하는 [PresentationText](../../presentationtext/) 인스턴스

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) 메서드

슬라이드에서 원시 텍스트를 가져옵니다

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 입력 스트림 |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 추출 모드 |

### 반환값

원시 슬라이드 텍스트를 나타내는 SlideText 배열을 포함하는 [PresentationText](../../presentationtext/) 인스턴스

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) 메서드

슬라이드에서 원시 텍스트를 가져옵니다

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 입력 스트림 |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | 추출 모드 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 로드 옵션 |

### 반환값

원시 슬라이드 텍스트를 나타내는 SlideText 배열을 포함하는 [PresentationText](../../presentationtext/) 인스턴스

## 참고

* 열거형 [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPresentationText](../../ipresentationtext/)
* 클래스 [String](../../../system/string/)
* 클래스 [PresentationFactory](../)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [ILoadOptions](../../iloadoptions/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)