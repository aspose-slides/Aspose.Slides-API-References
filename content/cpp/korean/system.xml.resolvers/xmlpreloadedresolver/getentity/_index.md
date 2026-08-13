---
title: GetEntity()
second_title: Aspose.Slides for C++ API 레퍼런스
description: URI를 실제 리소스를 포함하는 객체에 매핑합니다.
type: docs
weight: 53
url: /ko/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) 메서드

URI를 실제 리소스를 포함하는 객체에 매핑합니다.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/) 호출에서 반환된 URI. |
| role | [String](../../../system/string/) | 현재 사용되지 않음. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | 반환할 객체의 유형입니다. [XmlPreloadedResolver](../)는 [String](../../../system/string/) 로 추가된 URI에 대해 Stream 객체와 TextReader 객체를 지원합니다. 요청된 유형이 해결자에서 지원되지 않으면 예외가 발생합니다. XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) 메서드를 사용하여 이 해결자가 특정 **형식**을 지원하는지 확인하세요. |

### 반환 값

실제 소스에 해당하는 Stream 또는 TextReader 객체.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [Uri](../../../system/uri/)
* 클래스 [String](../../../system/string/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [XmlPreloadedResolver](../)
* 네임스페이스 [System::Xml::Resolvers](../../)
* 라이브러리 [Aspose.Slides](../../../)