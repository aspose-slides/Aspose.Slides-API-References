---
title: XmlPreloadedResolver()
second_title: Aspose.Slides for C++ API 참조
description: XmlPreloadedResolver 클래스의 새 인스턴스를 초기화합니다.
type: docs
weight: 27
url: /ko/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() 생성자

새로운 [XmlPreloadedResolver](../) 클래스 인스턴스를 초기화합니다.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) 생성자

지정된 사전 로드된 알려진 DTD와 함께 새로운 [XmlPreloadedResolver](../) 클래스 인스턴스를 초기화합니다.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | 캐시에 미리 채워야 하는 알려진 DTD |
 
## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) 생성자

지정된 폴백 해결자를 사용하여 새로운 [XmlPreloadedResolver](../) 클래스 인스턴스를 초기화합니다.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) 또는 자체 해결자 |
 
## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) 생성자

지정된 폴백 해결자와 사전 로드된 알려진 DTD를 사용하여 새로운 [XmlPreloadedResolver](../) 클래스 인스턴스를 초기화합니다.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) 또는 자체 해결자 |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | 캐시에 미리 채워야 하는 알려진 DTD |
 
## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) 생성자

지정된 폴백 해결자, 사전 로드된 알려진 DTD 및 URI 동등성 비교자를 사용하여 새로운 [XmlPreloadedResolver](../) 클래스 인스턴스를 초기화합니다.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) 또는 자체 해결자 |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | 캐시에 미리 채워야 하는 알려진 DTD |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | URI를 비교할 때 사용할 IEqualityComparer 인터페이스 구현 |
 
## 참고

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlPreloadedResolver](../)
* 클래스 [XmlResolver](../../../system.xml/xmlresolver/)
* 클래스 [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* 클래스 [Uri](../../../system/uri/)
* 네임스페이스 [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)