---
title: GetElementsByTagName()
second_title: Aspose.Slides for C++ API 참조
description: "지정된 XmlElement::get_Name와 일치하는 모든 하위 요소의 목록을 포함하는 XmlNodeList를 반환합니다."
type: docs
weight: 287
url: /ko/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) 메서드


지정된 [XmlElement::get_Name](../get_name/)와 일치하는 모든 하위 요소의 목록을 포함하는 [XmlNodeList](../../xmlnodelist/)를 반환합니다.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | 일치시킬 이름 태그입니다. 이것은 한정된 이름입니다. 일치하는 노드의 **get_Name** 값과 비교됩니다. 별표(*)는 모든 태그와 일치하는 특수 값입니다. |

### 반환값

일치하는 모든 노드의 목록을 포함하는 [XmlNodeList](../../xmlnodelist/)입니다. 일치하는 노드가 없으면 목록은 비어 있습니다.

## XmlElement::GetElementsByTagName(String, String) 메서드


지정된 [XmlElement::get_LocalName](../get_localname/) 및 [XmlElement::get_NamespaceURI](../get_namespaceuri/) 값과 일치하는 모든 하위 요소의 목록을 포함하는 [XmlNodeList](../../xmlnodelist/)를 반환합니다.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 일치시킬 로컬 이름입니다. 별표(*)는 모든 태그와 일치하는 특수 값입니다. |
| namespaceURI | [String](../../../system/string/) | 일치시킬 네임스페이스 URI입니다. |

### 반환값

일치하는 모든 노드의 목록을 포함하는 [XmlNodeList](../../xmlnodelist/)입니다. 일치하는 노드가 없으면 목록은 비어 있습니다.

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNodeList](../../xmlnodelist/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlElement](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)