---
title: get_OldValue()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 노드의 원래 값을 반환합니다.
type: docs
weight: 53
url: /ko/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() 메서드


노드의 원래 값을 반환합니다.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### 반환 값

노드의 원래 값입니다. 이 메서드는 노드가 속성이거나 텍스트 노드가 아니거나, 노드가 삽입 중인 경우 **nullptr**를 반환합니다. **XmlDocument::NodeChanging** 이벤트에서 호출되면 **get_OldValue**는 변경이 성공할 경우 교체될 현재 노드 값을 반환합니다. **XmlDocument::NodeChanged** 이벤트에서 호출되면 **get_OldValue**는 변경 전 노드의 값을 반환합니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlNodeChangedEventArgs](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)