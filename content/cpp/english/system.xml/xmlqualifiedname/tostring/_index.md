---
title: ToString()
second_title: Aspose.Slides for C++ API Reference
description: Returns the string value of the XmlQualifiedName.
type: docs
weight: 79
url: /system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const method


Returns the string value of the [XmlQualifiedName](../).

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```


### Return Value

The string value of the [XmlQualifiedName](../) in the format of **namespace:localname**. If the object does not have a namespace defined, this method returns just the local name.

## XmlQualifiedName::ToString(const String\&, const String\&) method


Returns the string value of the [XmlQualifiedName](../).

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | The name of the object. |
| ns | const [String](../../../system/string/)\& | The namespace of the object. |

### Return Value

The string value of the [XmlQualifiedName](../) in the format of **namespace:localname**. If the object does not have a namespace defined, this method returns just the local name.

## See Also

* Class [String](../../../system/string/)
* Class [XmlQualifiedName](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)