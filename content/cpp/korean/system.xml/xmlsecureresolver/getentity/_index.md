---
title: GetEntity()
second_title: Aspose.Slides for C++ API 참조
description: URI를 실제 리소스를 포함하는 객체에 매핑합니다.
type: docs
weight: 27
url: /ko/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) 메서드

URI를 실제 리소스를 포함하는 객체에 매핑합니다.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) 호출에서 반환된 URI |
| role | [String](../../../system/string/) | 현재 사용되지 않습니다. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | 반환할 객체의 유형입니다. 현재 버전은 Stream 객체만 반환합니다. |

### 반환 값

기본 [XmlResolver](../../xmlresolver/)에서 **GetEntity**를 호출하여 반환된 스트림입니다. 스트림이 아닌 다른 유형이 지정된 경우, 메서드는 **nullptr**를 반환합니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [Uri](../../../system/uri/)
* 클래스 [String](../../../system/string/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [XmlSecureResolver](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)