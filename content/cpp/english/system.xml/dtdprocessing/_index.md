---
title: DtdProcessing
second_title: Aspose.Slides for C++ API Reference
description: Specifies the options for processing DTDs. The DtdProcessing enumeration is used by the XmlReaderSettings class.
type: docs
weight: 638
url: /system.xml/dtdprocessing/
---
## DtdProcessing enum


Specifies the options for processing DTDs. The DtdProcessing enumeration is used by the [XmlReaderSettings](../xmlreadersettings/) class.

```cpp
enum class DtdProcessing
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Prohibit | 0 | Specifies that when a DTD is encountered, an XmlException is thrown with a message that states that DTDs are prohibited. This is the default behavior. |
| Ignore | 1 | Causes the DOCTYPE element to be ignored. No DTD processing occurs, and the DTD/DOCTYPE is lost on output. |
| Parse | 2 | Used for parsing DTDs. |

## See Also

* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)