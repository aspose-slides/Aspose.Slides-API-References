---
title: get_OldValue()
second_title: Aspose.Slides for C++ API Reference
description: Returns the original value of the node.
type: docs
weight: 53
url: /cpp/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() method


Returns the original value of the node.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### Return Value

The original value of the node. This method returns **nullptr** if the node is neither an attribute nor a text node, or if the node is being inserted. If called in a **XmlDocument::NodeChanging** event, **get_OldValue** returns the current value of the node that will be replaced if the change is successful. If called in a **XmlDocument::NodeChanged** event, **get_OldValue** returns the value of node prior to the change.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)