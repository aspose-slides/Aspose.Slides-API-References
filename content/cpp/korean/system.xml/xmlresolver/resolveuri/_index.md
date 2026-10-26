---
title: ResolveUri()
second_title: Aspose.Slides for C++ API 참조
description: 파생 클래스에서 재정의될 경우, 기본 URI와 상대 URI에서 절대 URI를 해결합니다.
type: docs
weight: 27
url: /ko/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) 메서드

When overridden in a derived class, resolves the absolute URI from the base and relative URIs.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 상대 URI를 해결하는 데 사용되는 기본 URI. |
| relativeUri | [String](../../../system/string/) | 해결할 URI입니다. URI는 절대 경로나 상대 경로가 될 수 있습니다. 절대 경로인 경우, 이 값은 **baseUri** 값을 실제로 대체합니다. 상대 경로인 경우, **baseUri**와 결합하여 절대 URI를 만듭니다. |

### 반환 값

절대 URI 또는 상대 URI를 해결할 수 없는 경우 **nullptr**.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)