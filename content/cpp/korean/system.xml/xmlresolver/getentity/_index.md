---
title: GetEntity()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 때, URI를 실제 리소스를 포함하는 객체에 매핑합니다.
type: docs
weight: 14
url: /ko/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) 메서드

When overridden in a derived class, maps a URI to an object that contains the actual resource.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/) 호출에서 반환된 URI. |
| role | [String](../../../system/string/) | 현재 사용되지 않음. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | 반환할 개체의 유형. 현재 버전은 Stream 개체만 반환합니다. |

### 반환값

스트림 개체 또는 스트림이 아닌 유형이 지정된 경우 **nullptr**.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [Uri](../../../system/uri/)
* 클래스 [String](../../../system/string/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [XmlResolver](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)