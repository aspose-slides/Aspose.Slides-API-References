---
title: XmlNodeChangedEventArgs()
second_title: Aspose.Slides for C++ API 참조
description: XmlNodeChangedEventArgs 클래스의 새 인스턴스를 초기화합니다.
type: docs
weight: 79
url: /ko/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) 생성자

새 인스턴스를 초기화합니다 [XmlNodeChangedEventArgs](../) 클래스.

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | 이 이벤트를 발생시킨 [XmlNode](../../xmlnode/). |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | 이 이벤트를 발생시킨 [XmlNode](../../xmlnode/)의 이전 상위 [XmlNode](../../xmlnode/). |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | 이 이벤트를 발생시킨 [XmlNode](../../xmlnode/)의 새 상위 [XmlNode](../../xmlnode/). |
| oldValue | const [String](../../../system/string/)\& | 이 이벤트를 발생시킨 [XmlNode](../../xmlnode/)의 이전 값. |
| newValue | const [String](../../../system/string/)\& | 이 이벤트를 발생시킨 [XmlNode](../../xmlnode/)의 새 값. |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | 해당 XmlNodeChangedAction. |

## 참조

* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlNodeChangedEventArgs](../)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)