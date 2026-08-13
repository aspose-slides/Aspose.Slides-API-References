---
title: ReadAttributeValue()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 속성 값을 하나 이상의 Text, EntityReference, 또는 EndEntity 노드로 구문 분석합니다.
type: docs
weight: 560
url: /ko/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue() 메서드


속성 값을 하나 이상의 **[Text](../../../system.text/)**, **EntityReference**, 또는 **EndEntity** 노드로 구문 분석합니다.

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```


### 반환 값

**true**는 반환할 노드가 있을 때입니다. **false**는 초기 호출 시 리더가 속성 노드에 위치하지 않았거나 모든 속성 값이 읽힌 경우입니다. **misc=\"\"**와 같은 빈 속성은 값을 [String::Empty](../../../system/string/empty/)인 단일 노드와 함께 **true**를 반환합니다.

## 참조

* 클래스 [XmlTextReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)