---
title: get_IndentChars()
second_title: Aspose.Slides for C++ API Reference
description: "Returns the character string to use when indenting. This setting is used when the XmlWriterSettings::set_Indent value is set to true."
type: docs
weight: 131
url: /system.xml/xmlwritersettings/get_indentchars/
---
## XmlWriterSettings::get_IndentChars() method


Returns the character string to use when indenting. This setting is used when the [XmlWriterSettings::set_Indent](../set_indent/) value is set to **true**.

```cpp
String System::Xml::XmlWriterSettings::get_IndentChars()
```


### Return Value

The character string to use when indenting. This can be set to any string value. However, to ensure valid XML, you should specify only valid white space characters, such as space characters, tabs, carriage returns, or line feeds. The default is two spaces.

## See Also

* Class [String](../../../system/string/)
* Class [XmlWriterSettings](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)