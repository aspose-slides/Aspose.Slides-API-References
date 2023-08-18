---
title: WriteAttributes()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, writes out all the attributes found at the current position in the XmlReader.
type: docs
weight: 417
url: /system.xml/xmlwriter/writeattributes/
---
## XmlWriter::WriteAttributes(SharedPtr\<XmlReader\>, bool) method


When overridden in a derived class, writes out all the attributes found at the current position in the [XmlReader](../../xmlreader/).

```cpp
virtual void System::Xml::XmlWriter::WriteAttributes(SharedPtr<XmlReader> reader, bool defattr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | The [XmlReader](../../xmlreader/) from which to copy the attributes. |
| defattr | **bool** | **true** to copy the default attributes from the [XmlReader](../../xmlreader/); otherwise, **false**. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlWriter](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)