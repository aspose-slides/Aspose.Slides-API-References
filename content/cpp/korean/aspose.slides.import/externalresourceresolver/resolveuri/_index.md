---
title: ResolveUri()
second_title: Aspose.Slides for C++ API 참조
description: 기본 및 상대 URI에서 절대 URI를 해결합니다.
type: docs
weight: 1
url: /ko/aspose.slides.import/externalresourceresolver/resolveuri/
---
## ExternalResourceResolver::ResolveUri(System::String, System::String) 메서드

기본 URI와 상대 URI에서 절대 URI를 해결합니다.

```cpp
System::String Aspose::Slides::Import::ExternalResourceResolver::ResolveUri(System::String baseUri, System::String relativeUri) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| baseUri | [System::String](../../../system/string/) | 링크 객체의 기본 URI |
| relativeUri | [System::String](../../../system/string/) | 연결된 객체에 대한 상대 URI |

### 반환 값

절대 URI를 반환하며, 상대 URI를 해결할 수 없을 경우 null을 반환합니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [ExternalResourceResolver](../)
* 네임스페이스 [Aspose::Slides::Import](../../)
* 라이브러리 [Aspose.Slides](../../../)