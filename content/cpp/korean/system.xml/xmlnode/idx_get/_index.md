---
title: idx_get()
second_title: Aspose.Slides for C++ API 참조
description: "지정된 XmlNode::get_Name을(를) 가진 첫 번째 자식 요소를 반환합니다."
type: docs
weight: 586
url: /ko/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) 메서드

지정된 [XmlNode::get_Name](../get_name/)을(를) 가진 첫 번째 자식 요소를 반환합니다.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 검색할 요소의 정규화된 이름입니다. |

### 반환값

지정된 이름과 일치하는 첫 번째 [XmlElement](../../xmlelement/)입니다. 일치하는 항목이 없으면 **nullptr**를 반환합니다.

## XmlNode::idx_get(String, String) 메서드

지정된 [XmlNode::get_LocalName](../get_localname/) 및 [XmlNode::get_NamespaceURI](../get_namespaceuri/) 값을 가진 첫 번째 자식 요소를 반환합니다.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localname | [String](../../../system/string/) | 요소의 로컬 이름입니다. |
| ns | [String](../../../system/string/) | 요소의 네임스페이스 URI입니다. |

### 반환값

일치하는 **localname** 및 **ns**를 가진 첫 번째 [XmlElement](../../xmlelement/)입니다. 일치하는 항목이 없으면 **nullptr**를 반환합니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlElement](../../xmlelement/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlNode](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)