---
title: ReadString()
second_title: Aspose.Slides for C++ API 참조
description: 요소 또는 텍스트 노드의 내용을 문자열로 읽습니다.
type: docs
weight: 391
url: /ko/system.xml/xmlnodereader/readstring/
---
## XmlNodeReader::ReadString() 메서드

요소 또는 텍스트 노드의 내용을 문자열로 읽습니다.

```cpp
String System::Xml::XmlNodeReader::ReadString() override
```

### Return Value

요소 또는 텍스트와 유사한 노드의 내용(CDATA, [Text](../../../system.text/) 노드 등 포함 가능). 리더가 요소나 텍스트 노드가 아닌 위치에 있거나 현재 컨텍스트에서 반환할 텍스트 내용이 더 이상 없을 경우 빈 문자열이 될 수 있습니다. 참고: 텍스트 노드는 요소이거나 속성 텍스트 노드일 수 있습니다.

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlNodeReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)