---
title: SupportsType()
second_title: Aspose.Slides for C++ API 참조
description: 리졸버가 Stream 외에 다른 유형을 지원하는지 확인합니다.
type: docs
weight: 66
url: /ko/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) 메서드

해당 리졸버가 Stream 이외의 다른 유형을 지원하는지 확인합니다.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 확인할 절대 URI. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | 반환할 유형. |

### 반환 값

Type이 지원되는 경우 **true**, 그렇지 않으면 **false**.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Uri](../../../system/uri/)
* 클래스 [TypeInfo](../../../system/typeinfo/)
* 클래스 [XmlPreloadedResolver](../)
* 네임스페이스 [System::Xml::Resolvers](../../)
* 라이브러리 [Aspose.Slides](../../../)