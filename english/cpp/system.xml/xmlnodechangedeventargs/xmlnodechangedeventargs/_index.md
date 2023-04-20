---
title: XmlNodeChangedEventArgs()
second_title: Aspose.Slides for C++ API Reference
description: Initializes a new instance of the XmlNodeChangedEventArgs class.
type: docs
weight: 79
url: /cpp/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) constructor


Initializes a new instance of the [XmlNodeChangedEventArgs](../) class.

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | The [XmlNode](../../xmlnode/) that generated the event. |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | The old parent [XmlNode](../../xmlnode/) of the [XmlNode](../../xmlnode/) that generated the event. |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | The new parent [XmlNode](../../xmlnode/) of the [XmlNode](../../xmlnode/) that generated the event. |
| oldValue | const [String](../../../system/string/)\& | The old value of the [XmlNode](../../xmlnode/) that generated the event. |
| newValue | const [String](../../../system/string/)\& | The new value of the [XmlNode](../../xmlnode/) that generated the event. |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | The XmlNodeChangedAction. |

## See Also

* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)