---
title: Save()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 형식으로 프레젠테이션의 모든 슬라이드를 파일에 저장합니다.
type: docs
weight: 404
url: /ko/aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) 메서드

지정된 형식으로 프레젠테이션의 모든 슬라이드를 파일에 저장합니다.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | 생성된 파일에 대한 경로. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 내보낸 데이터의 형식. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) 메서드

지정된 형식으로 프레젠테이션의 모든 슬라이드를 스트림에 저장합니다.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 출력 스트림. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 내보낸 데이터의 형식. |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) 메서드

지정된 형식과 추가 옵션으로 프레젠테이션의 모든 슬라이드를 파일에 저장합니다.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | 생성된 파일에 대한 경로. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 내보낸 데이터의 형식. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | 추가 형식 옵션. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) 메서드

지정된 형식과 추가 옵션으로 프레젠테이션의 모든 슬라이드를 스트림에 저장합니다.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 출력 스트림. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 내보낸 데이터의 형식. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | 추가 형식 옵션. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) 메서드

지정된 슬라이드를 지정된 형식으로 파일에 저장합니다.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | 생성된 파일에 대한 경로. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 슬라이드 위치 배열, 1부터 시작합니다. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 내보낸 데이터의 형식. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) 메서드

지정된 슬라이드를 지정된 형식으로 파일에 저장합니다.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | 생성된 파일에 대한 경로. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 슬라이드 위치 배열, 1부터 시작합니다. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 내보낸 데이터의 형식. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | 추가 형식 옵션. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) 메서드

지정된 슬라이드를 지정된 형식으로 스트림에 저장합니다.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 출력 스트림. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 슬라이드 위치 배열, 1부터 시작합니다. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 내보낸 데이터의 형식. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) 메서드

지정된 슬라이드를 지정된 형식으로 스트림에 저장합니다.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 출력 스트림. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 슬라이드 위치 배열, 1부터 시작합니다. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | 내보낸 데이터의 형식. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | 추가 형식 옵션. |

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) 메서드

프레젠테이션의 모든 슬라이드를 XAML 마크업을 나타내는 파일 집합에 저장합니다.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | XAML 형식 옵션. |

## 비고

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## 참고

* 열거형 [SaveFormat](../../../aspose.slides.export/saveformat/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [IPresentation](../)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* 클래스 [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)