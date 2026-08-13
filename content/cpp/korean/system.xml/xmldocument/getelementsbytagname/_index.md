---
title: GetElementsByTagName()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 이름과 일치하는 모든 하위 요소들의 목록을 포함하는 XmlNodeList를 반환합니다.
type: docs
weight: 443
url: /ko/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) 메서드


지정된 이름과 일치하는 모든 하위 요소들의 목록을 포함하는 [XmlNodeList](../../xmlnodelist/)를 반환합니다.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 일치시킬 정규화된 이름입니다. 일치하는 노드의 **get_Name** 값과 비교됩니다. 특수 값 **\"*\"** 은 모든 태그와 일치합니다. |

### 반환 값

일치하는 모든 노드의 목록을 포함하는 [XmlNodeList](../../xmlnodelist/)를 반환합니다. **name** 과 일치하는 노드가 없으면 반환된 컬렉션은 비어 있습니다.

## XmlDocument::GetElementsByTagName(String, String) 메서드


지정된 [XmlDocument::get_LocalName](../get_localname/) 및 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)와 일치하는 모든 하위 요소들의 목록을 포함하는 [XmlNodeList](../../xmlnodelist/)를 반환합니다.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 일치시킬 LocalName입니다. 특수 값 **\"*\"** 은 모든 태그와 일치합니다. |
| namespaceURI | [String](../../../system/string/) | 일치시킬 NamespaceURI입니다. |

### 반환 값

일치하는 모든 노드의 목록을 포함하는 [XmlNodeList](../../xmlnodelist/)를 반환합니다. 지정된 **localName** 및 **namespaceURI** 와 일치하는 노드가 없으면 반환된 컬렉션은 비어 있습니다.

## 또 보기

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNodeList](../../xmlnodelist/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlDocument](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)