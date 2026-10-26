---
title: ReadAttributeValue()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, 속성 값을 하나 이상의 Text, EntityReference 또는 EndEntity 노드로 구문 분석합니다.
type: docs
weight: 677
url: /ko/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() 메서드


파생 클래스에서 재정의될 경우, 속성 값을 하나 이상의 **[Text](../../../system.text/)**, **EntityReference**, 또는 **EndEntity** 노드로 구문 분석합니다.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```


### 반환 값

**true** 반환할 노드가 있는 경우. **false** 초기 호출 시 리더가 속성 노드에 위치하지 않거나 모든 속성 값이 읽힌 경우. 예를 들어 **misc=\"\"**와 같은 빈 속성은 값이 [String::Empty](../../../system/string/empty/)인 단일 노드와 함께 **true**를 반환합니다.

## 참고

* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)