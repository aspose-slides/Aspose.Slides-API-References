---
title: ResolveUri()
second_title: Aspose.Slides for C++ API 참조
description: 기본 URI와 상대 URI에서 절대 URI를 해석합니다.
type: docs
weight: 66
url: /ko/system.xml/xmlurlresolver/resolveuri/
---
## XmlUrlResolver::ResolveUri(SharedPtr\<Uri\>, String) 메서드

기본 URI와 상대 URI로부터 절대 URI를 해석합니다.

```cpp
SharedPtr<Uri> System::Xml::XmlUrlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 상대 URI를 해석하는 데 사용되는 기본 URI입니다. |
| relativeUri | [String](../../../system/string/) | 해석할 URI입니다. URI는 절대이거나 상대일 수 있습니다. 절대인 경우, 이 값은 **baseUri** 값을 실질적으로 대체합니다. 상대인 경우, **baseUri**와 결합되어 절대 URI를 만듭니다. |

### 반환 값

절대 URI이며, 상대 URI를 해석할 수 없는 경우 **nullptr**를 반환합니다.

## 관련 항목

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Uri](../../../system/uri/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlUrlResolver](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)