---
title: MoveToContent()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "현재 노드가 콘텐츠(공백이 아닌 텍스트, CDATA, Element, EndElement, EntityReference, 또는 EndEntity) 노드인지 확인합니다. 노드가 콘텐츠 노드가 아닌 경우, 리더는 다음 콘텐츠 노드 또는 파일 끝까지 앞으로 건너뜁니다. 다음 유형의 노드는 건너뜁니다: ProcessingInstruction, DocumentType, Comment, Whitespace, 또는 SignificantWhitespace."
type: docs
weight: 833
url: /ko/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() 메서드

현재 노드가 콘텐츠(공백이 아닌 텍스트, **CDATA**, **Element**, **EndElement**, **EntityReference**, 또는 **EndEntity**) 노드인지 확인합니다. 노드가 콘텐츠가 아닌 경우, 리더는 다음 콘텐츠 노드 또는 파일 끝까지 앞으로 건너뜁니다. 다음 유형의 노드는 건너뜁니다: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, 또는 **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```

### 반환 값

메서드에 의해 찾은 현재 노드의 [XmlReader::get_NodeType](../get_nodetype/) 값이거나, 리더가 입력 스트림의 끝에 도달한 경우 [XmlNodeType::None](../../xmlnodetype/) 입니다.

## 관련 항목

* Enum [XmlNodeType](../../xmlnodetype/)
* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)