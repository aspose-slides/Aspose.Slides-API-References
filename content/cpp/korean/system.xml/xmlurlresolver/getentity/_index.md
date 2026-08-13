---
title: GetEntity()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 실제 리소스를 포함하는 객체에 URI를 매핑합니다.
type: docs
weight: 53
url: /ko/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) 메서드

URI를 실제 리소스를 포함하는 객체에 매핑합니다.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/) 호출에서 반환된 URI. |
| role | [String](../../../system/string/) | 현재 사용되지 않습니다. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | 반환할 객체의 유형입니다. 현재 구현에서는 Stream 객체만 반환합니다. |

### 반환 값

스트림 객체 또는 스트림이 아닌 유형이 지정된 경우 **nullptr**.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [Uri](../../../system/uri/)
* 클래스 [String](../../../system/string/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [XmlUrlResolver](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)