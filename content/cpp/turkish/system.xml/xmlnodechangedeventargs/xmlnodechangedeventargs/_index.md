---
title: XmlNodeChangedEventArgs()
second_title: Aspose.Slides for C++ API Referansı
description: XmlNodeChangedEventArgs sınıfının yeni bir örneğini başlatır.
type: docs
weight: 79
url: /tr/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) constructor

Yeni bir [XmlNodeChangedEventArgs](../) sınıfının örneğini başlatır.

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Olayı oluşturan [XmlNode](../../xmlnode/). |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Olayı oluşturan [XmlNode](../../xmlnode/)'in eski [XmlNode](../../xmlnode/). |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Olayı oluşturan [XmlNode](../../xmlnode/)'in yeni [XmlNode](../../xmlnode/). |
| oldValue | const [String](../../../system/string/)\& | Olayı oluşturan [XmlNode](../../xmlnode/)'in eski değeri. |
| newValue | const [String](../../../system/string/)\& | Olayı oluşturan [XmlNode](../../xmlnode/)'in yeni değeri. |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | XmlNodeChangedAction. |

## Diğer Bilgiler

* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNode](../../xmlnode/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlNodeChangedEventArgs](../)
* İsim Uzayı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)