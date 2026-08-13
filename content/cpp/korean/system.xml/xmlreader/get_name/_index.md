---
title: get_Name()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의되면 현재 노드의 정규화된 이름을 가져옵니다.
type: docs
weight: 27
url: /ko/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() 메서드


파생 클래스에서 재정의되면 현재 노드의 정규화된 이름을 가져옵니다.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```


### 반환 값

현재 노드의 정규화된 이름입니다. 예를 들어, **Name**은 요소 **<bk:book>**에 대해 **bk:book**입니다.

## 비고



반환된 이름은 노드의 [XmlReader::get_NodeType](../get_nodetype/) 값에 따라 결정됩니다. 다음 노드 유형은 나열된 값을 반환합니다. 다른 모든 노드 유형은 빈 문자열을 반환합니다. 

| Node type | Name |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| 속성의 이름. |
| `DocumentType`| 문서 유형 이름. |
| `Element`| 태그 이름. |
| `EntityReference`| 참조된 엔터티의 이름. |
| `ProcessingInstruction`| 프로세싱 명령의 대상. |
| [XmlDeclaration](../../xmldeclaration/)| 리터럴 문자열 `xml`. |


## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)