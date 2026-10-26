---
title: SupportsType()
second_title: Aspose.Slides용 C++ API 레퍼런스
description: 해결 프로그램이 Stream이 아닌 다른 유형을 반환하도록 합니다.
type: docs
weight: 40
url: /ko/system.xml/xmlresolver/supportstype/
---
## XmlResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) 메서드


해결 프로그램이 Stream이 아닌 다른 유형을 반환하도록 합니다.

```cpp
virtual bool System::Xml::XmlResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type)
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | 반환할 유형. |

### 반환값

**true**는 **type**이 지원되는 경우; 그렇지 않으면 **false**.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)