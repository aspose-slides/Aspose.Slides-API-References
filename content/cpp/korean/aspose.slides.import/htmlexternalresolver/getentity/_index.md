---
title: GetEntity()
second_title: Aspose.Slides for C++ API 레퍼런스
description: URI를 실제 리소스를 포함하는 객체에 매핑합니다.
type: docs
weight: 14
url: /ko/aspose.slides.import/htmlexternalresolver/getentity/
---
## HtmlExternalResolver::GetEntity(System::String) 메서드

URI를 실제 리소스를 포함하는 객체에 매핑합니다.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Slides::Import::HtmlExternalResolver::GetEntity(System::String absoluteUri) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| absoluteUri | [System::String](../../../system/string/) | 객체에 대한 절대 URI. |

### 반환값

[System::IO::Stream](../../../system.io/stream/) 객체 또는 리소스를 스트리밍할 수 없는 경우 null.

## 또한 보기

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [String](../../../system/string/)
* 클래스 [HtmlExternalResolver](../)
* 네임스페이스 [Aspose::Slides::Import](../../)
* 라이브러리 [Aspose.Slides](../../../)