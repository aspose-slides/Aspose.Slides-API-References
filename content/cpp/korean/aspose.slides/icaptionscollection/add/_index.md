---
title: Add()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션 끝에 WebVTT 닫힌 캡션을 추가합니다.
type: docs
weight: 27
url: /ko/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) 메서드

컬렉션 끝에 WebVTT 닫힌 캡션을 추가합니다.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | 닫힌 캡션의 레이블입니다. |
| filePath | [System::String](../../../system/string/) | WebVTT 파일의 경로입니다. |

### 반환 값

추가된 [ICaptions](../../icaptions/) 인스턴스입니다.

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) 메서드

스트림에서 컬렉션 끝에 WebVTT 닫힌 캡션을 추가합니다.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | 닫힌 캡션의 레이블입니다. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | WebVTT 형식의 데이터를 포함하는 입력 스트림입니다. |

### 반환 값

추가된 [ICaptions](../../icaptions/) 인스턴스입니다.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ICaptions](../../icaptions/)
* 클래스 [String](../../../system/string/)
* 클래스 [ICaptionsCollection](../)
* 클래스 [Stream](../../../system.io/stream/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)