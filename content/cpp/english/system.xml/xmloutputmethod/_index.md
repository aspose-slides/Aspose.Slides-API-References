---
title: XmlOutputMethod
second_title: Aspose.Slides for C++ API Reference
description: Specifies the method used to serialize the XmlWriter output.
type: docs
weight: 846
url: /system.xml/xmloutputmethod/
---
## XmlOutputMethod enum


Specifies the method used to serialize the [XmlWriter](../xmlwriter/) output.

```cpp
enum class XmlOutputMethod
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Xml | 0 | Serialize according to the XML 1.0 rules. |
| Html | 1 | Serialize according to the HTML rules specified by XSLT. |
| Text | 2 | Serialize text blocks only. |
| AutoDetect | 3 | Use the XSLT rules to choose between the [XmlOutputMethod::Xml](./) and [XmlOutputMethod::Html](./) output methods at runtime. |

## See Also

* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)