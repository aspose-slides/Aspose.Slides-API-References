---
title: Add()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션의 끝에 WebVTT 폐쇄 캡션을 추가합니다.
type: docs
weight: 27
url: /ko/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) 메서드

컬렉션의 끝에 WebVTT 폐쇄 캡션을 추가합니다.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | 폐쇄 캡션의 레이블. |
| filePath | [System::String](../../../system/string/) | WebVTT 파일의 경로. |

### 반환값

추가된 [ICaptions](../../icaptions/) 인스턴스.

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) 메서드

스트림에서 컬렉션의 끝에 WebVTT 폐쇄 캡션을 추가합니다.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | 폐쇄 캡션의 레이블. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | WebVTT 형식의 데이터를 포함하는 입력 스트림. |

### 반환값

추가된 [ICaptions](../../icaptions/) 인스턴스.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ICaptions](../../icaptions/)
* 클래스 [String](../../../system/string/)
* 클래스 [CaptionsCollection](../)
* 클래스 [Stream](../../../system.io/stream/)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)