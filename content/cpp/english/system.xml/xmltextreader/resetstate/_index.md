---
title: ResetState()
second_title: Aspose.Slides for C++ API Reference
description: "Resets the state of the reader to ReadState::Initial."
type: docs
weight: 729
url: /system.xml/xmltextreader/resetstate/
---
## XmlTextReader::ResetState() method


Resets the state of the reader to [ReadState::Initial](../../readstate/).

```cpp
void System::Xml::XmlTextReader::ResetState()
```


### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | Calling **ResetState** if the reader was constructed using an [XmlParserContext](../../xmlparsercontext/). |
| XmlException | Documents in a single stream do not share the same encoding. |


## See Also

* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)