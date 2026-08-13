---
title: ReadToDescendant()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 한정 이름을 가진 다음 하위 요소로 XmlReader를 이동시킵니다.
type: docs
weight: 911
url: /ko/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) 메서드


[XmlReader](../)를 지정된 한정 이름을 가진 다음 하위 요소로 이동시킵니다.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 이동하려는 요소의 한정 이름입니다. |

### 반환값

**true** 매칭되는 하위 요소가 발견되면; 그렇지 않으면 **false**. 매칭되는 자식 요소를 찾지 못하면, [XmlReader](../)가 요소의 종료 태그([XmlReader::get_NodeType](../get_nodetype/) 값이 [XmlNodeType::EndElement](../../xmlnodetype/))에 위치합니다. [XmlReader::ReadToDescendant(String)](./)가 호출될 때 [XmlReader](../)가 요소에 위치하지 않은 경우, 이 메서드는 **false**를 반환하며 [XmlReader](../)의 위치는 변경되지 않습니다.

## XmlReader::ReadToDescendant(String, String) 메서드


[XmlReader](../)를 지정된 로컬 이름 및 네임스페이스 URI를 가진 다음 하위 요소로 이동시킵니다.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 이동하려는 요소의 로컬 이름입니다. |
| namespaceURI | [String](../../../system/string/) | 이동하려는 요소의 네임스페이스 URI입니다. |

### 반환값

**true** 매칭되는 하위 요소가 발견되면; 그렇지 않으면 **false**. 매칭되는 자식 요소를 찾지 못하면, [XmlReader](../)가 요소의 종료 태그([XmlReader::get_NodeType](../get_nodetype/) 값이 [XmlNodeType::EndElement](../../xmlnodetype/))에 위치합니다. [XmlReader::ReadToDescendant(String,String)](./)가 호출될 때 [XmlReader](../)가 요소에 위치하지 않은 경우, 이 메서드는 **false**를 반환하며 [XmlReader](../)의 위치는 변경되지 않습니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)