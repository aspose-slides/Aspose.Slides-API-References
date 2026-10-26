---
title: XmlNodeChangedEventArgs()
second_title: راهنمای API Aspose.Slides برای C++
description: یک نمونه جدید از کلاس XmlNodeChangedEventArgs را مقداردهی اولیه می‌کند.
type: docs
weight: 79
url: /fa/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) constructor

یک نمونه جدید از کلاس [XmlNodeChangedEventArgs](../) را مقداردهی اولیه می‌کند.

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | [XmlNode](../../xmlnode/)ی که رویداد را ایجاد کرد. |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | والد قبلی [XmlNode](../../xmlnode/) [XmlNode](../../xmlnode/) که رویداد را ایجاد کرد. |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | والد جدید [XmlNode](../../xmlnode/) [XmlNode](../../xmlnode/) که رویداد را ایجاد کرد. |
| oldValue | const [String](../../../system/string/)\& | مقدار قبلی [XmlNode](../../xmlnode/) که رویداد را ایجاد کرد. |
| newValue | const [String](../../../system/string/)\& | مقدار جدید [XmlNode](../../xmlnode/) که رویداد را ایجاد کرد. |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | XmlNodeChangedAction. |

## موارد مرتبط

* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNode](../../xmlnode/)
* کلاس [String](../../../system/string/)
* کلاس [XmlNodeChangedEventArgs](../)
* فضای نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)