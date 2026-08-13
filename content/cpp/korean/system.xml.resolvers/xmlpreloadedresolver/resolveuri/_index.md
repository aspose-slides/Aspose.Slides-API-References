---
title: ResolveUri()
second_title: Aspose.Slides for C++ API 참조
description: 기본 URI와 상대 URI에서 절대 URI를 해결합니다.
type: docs
weight: 40
url: /ko/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) 메서드


절대 URI를 기본 URI와 상대 URI에서 해결합니다.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 상대 URI를 해결하는 데 사용되는 기본 URI. |
| relativeUri | [String](../../../system/string/) | 해결할 URI입니다. URI는 절대 또는 상대일 수 있습니다. 절대인 경우, 이 값은 **baseUri** 값을 실제로 대체합니다. 상대인 경우, **baseUri**와 결합되어 절대 URI를 만듭니다. |

### 반환값

[Uri](../../../system/uri/)는 절대 URI를 나타내며, 상대 URI를 해결할 수 없는 경우 **nullptr**를 반환합니다.

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Uri](../../../system/uri/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlPreloadedResolver](../)
* 네임스페이스 [System::Xml::Resolvers](../../)
* 라이브러리 [Aspose.Slides](../../../)