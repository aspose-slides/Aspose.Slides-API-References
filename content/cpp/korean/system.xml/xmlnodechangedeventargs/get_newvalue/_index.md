---
title: get_NewValue()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 노드의 새 값을 반환합니다.
type: docs
weight: 66
url: /ko/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() 메서드

노드의 새로운 값을 반환합니다.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```

### 반환 값

노드의 새로운 값입니다. 이 메서드는 노드가 속성이 아니고 텍스트 노드도 아니며, 혹은 노드가 제거되는 경우 **nullptr**를 반환합니다. **XmlDocument::NodeChanging** 이벤트에서 호출된 경우, 변경이 성공하면 **get_NewValue**는 노드의 값을 반환합니다. **XmlDocument::NodeChanged** 이벤트에서 호출된 경우, **get_NewValue**는 노드의 현재 값을 반환합니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlNodeChangedEventArgs](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)