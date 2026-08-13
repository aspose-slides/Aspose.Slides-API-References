---
title: ResolveUri()
second_title: Aspose.Slides C++ API 참조
description: 기본 URI와 상대 URI에서 절대 URI를 해결합니다.
type: docs
weight: 1
url: /ko/aspose.slides.import/iexternalresourceresolver/resolveuri/
---
## IExternalResourceResolver::ResolveUri(System::String, System::String) 메서드

기본 URI와 상대 URI에서 절대 URI를 해결합니다.

```cpp
virtual System::String Aspose::Slides::Import::IExternalResourceResolver::ResolveUri(System::String baseUri, System::String relativeUri)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| baseUri | [System::String](../../../system/string/) | 링크된 객체의 기본 URI |
| relativeUri | [System::String](../../../system/string/) | 링크된 객체에 대한 상대 URI |

### 반환 값

상대 URI를 해결할 수 없을 경우 절대 URI 또는 null.

## 관련 항목

* 클래스 [String](../../../system/string/)
* 클래스 [IExternalResourceResolver](../)
* 네임스페이스 [Aspose::Slides::Import](../../)
* 라이브러리 [Aspose.Slides](../../../)