---
title: ResolveEntity()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, resolves the entity reference for EntityReference nodes.
type: docs
weight: 742
url: /system.xml/xmlreader/resolveentity/
---
## XmlReader::ResolveEntity() method


When overridden in a derived class, resolves the entity reference for **EntityReference** nodes.

```cpp
virtual void System::Xml::XmlReader::ResolveEntity()=0
```


### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | The reader is not positioned on an **EntityReference** node; this implementation of the reader cannot resolve entities ([XmlReader::get_CanResolveEntity](../get_canresolveentity/) returns **false**). |


## See Also

* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)