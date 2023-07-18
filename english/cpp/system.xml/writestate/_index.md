---
title: WriteState
second_title: Aspose.Slides for C++ API Reference
description: Specifies the state of the XmlWriter.
type: docs
weight: 755
url: /cpp/system.xml/writestate/
---
## WriteState enum


Specifies the state of the [XmlWriter](../xmlwriter/).

```cpp
enum class WriteState
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Start | 0 | Indicates that the XmlWriter::Write method has not yet been called. |
| Prolog | 1 | Indicates that the prolog is being written. |
| Element | 2 | Indicates that an element start tag is being written. |
| Attribute | 3 | Indicates that an attribute value is being written. |
| Content | 4 | Indicates that element content is being written. |
| Closed | 5 | Indicates that the [XmlWriter::Close](../xmlwriter/close/) method has been called. |
| Error | 6 | An exception has been thrown, which has left the [XmlWriter](../xmlwriter/) in an invalid state. You can call the [XmlWriter::Close](../xmlwriter/close/) method to put the [XmlWriter](../xmlwriter/) in the [WriteState::Closed](./) state. Any other [XmlWriter](../xmlwriter/) method calls results in an InvalidOperationException. |

## See Also

* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)