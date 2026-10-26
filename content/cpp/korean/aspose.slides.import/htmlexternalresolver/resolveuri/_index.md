---
title: ResolveUri()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 베이스와 상대 URI로부터 절대 URI를 해석합니다.
type: docs
weight: 1
url: /ko/aspose.slides.import/htmlexternalresolver/resolveuri/
---
## HtmlExternalResolver::ResolveUri(System::String, System::String) 메서드


베이스 URI와 상대 URI로부터 절대 URI를 해석합니다.

```cpp
System::String Aspose::Slides::Import::HtmlExternalResolver::ResolveUri(System::String baseUri, System::String relativeUri) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| baseUri | [System::String](../../../system/string/) | 링크된 객체의 기본 URI |
| relativeUri | [System::String](../../../system/string/) | 링크된 객체에 대한 상대 URI. |

### 반환 값

상대 URI를 해결할 수 없을 경우 절대 URI 또는 null.

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [HtmlExternalResolver](../)
* 네임스페이스 [Aspose::Slides::Import](../../)
* 라이브러리 [Aspose.Slides](../../../)