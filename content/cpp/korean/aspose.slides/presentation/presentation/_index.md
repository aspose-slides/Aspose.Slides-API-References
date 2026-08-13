---
title: Presentation()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 생성자는 새 프레젠테이션을 처음부터 생성합니다. 생성된 프레젠테이션에는 빈 슬라이드가 하나 있습니다.
type: docs
weight: 417
url: /ko/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() 생성자

이 생성자는 새 presentation을 처음부터 생성합니다. 생성된 presentation에는 빈 슬라이드가 하나 있습니다.

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) 생성자

이 생성자는 새 presentation을 처음부터 생성합니다. 생성된 presentation에는 빈 슬라이드가 하나 있습니다.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Additional load options. |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) 생성자

이 생성자는 기존 [Presentation](../)를 읽기 위한 기본 메커니즘입니다.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Input stream. |

## 비고

```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) 생성자

이 생성자는 기존 [Presentation](../)를 읽기 위한 기본 메커니즘입니다.

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Input stream. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Additional load options. |

## Presentation::Presentation(System::String) 생성자

이 생성자는 [Presentation](../)의 내용을 읽어들이는 소스 파일 경로를 가져옵니다.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Input file. |

## 비고

```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) 생성자

이 생성자는 [Presentation](../)의 내용을 읽어들이는 소스 파일 경로를 가져옵니다.

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Input file. |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | Additional load options. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Presentation](../)
* 클래스 [LoadOptions](../../loadoptions/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)