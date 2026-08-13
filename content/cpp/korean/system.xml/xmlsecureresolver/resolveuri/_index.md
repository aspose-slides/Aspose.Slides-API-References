---
title: ResolveUri()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 기본 및 상대 URI에서 절대 URI를 해결하기 위해 기본 XmlResolver의 ResolveUri를 호출합니다.
type: docs
weight: 40
url: /ko/system.xml/xmlsecureresolver/resolveuri/
---
## XmlSecureResolver::ResolveUri(SharedPtr\<Uri\>, String) 메서드

기본 및 상대 URI로부터 절대 URI를 해결하기 위해 기본 [XmlResolver](../../xmlresolver/)에서 **ResolveUri**를 호출합니다.

```cpp
SharedPtr<Uri> System::Xml::XmlSecureResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 상대 URI를 해결하는 데 사용되는 기본 URI. |
| relativeUri | [String](../../../system/string/) | 해결할 URI. URI는 절대이거나 상대일 수 있습니다. 절대인 경우, 이 값은 **baseUri** 값을 실질적으로 대체합니다. 상대인 경우, **baseUri**와 결합하여 절대 URI를 만듭니다. |

### 반환값

절대 URI 또는 상대 URI를 해결할 수 없을 경우 **nullptr** (기본 [XmlResolver](../../xmlresolver/)에서 **ResolveUri**를 호출하여 반환).

## 참고

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Uri](../../../system/uri/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlSecureResolver](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)