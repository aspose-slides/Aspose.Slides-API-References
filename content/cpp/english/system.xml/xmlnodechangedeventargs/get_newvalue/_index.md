---
title: get_NewValue()
second_title: Aspose.Slides for C++ API Reference
description: Returns the new value of the node.
type: docs
weight: 66
url: /system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() method


Returns the new value of the node.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```


### Return Value

The new value of the node. This method returns **nullptr** if the node is neither an attribute nor a text node, or if the node is being removed. If called in a **XmlDocument::NodeChanging** event, **get_NewValue** returns the value of the node if the change is successful. If called in a **XmlDocument::NodeChanged** event, **get_NewValue** returns the current value of the node.

## See Also

* Class [String](../../../system/string/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)