---
title: SetContext()
second_title: Referensi API Aspose.Slides untuk C++
description: Saat dioverride pada kelas turunan, menentukan objek XmlNamespaceManager yang digunakan untuk resolusi namespace.
type: docs
weight: 53
url: /id/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) metode

Saat dioverride pada kelas turunan, menentukan objek [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) yang digunakan untuk resolusi namespace.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | Sebuah objek [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) yang digunakan untuk resolusi namespace. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) metode

Saat dioverride pada kelas turunan, menentukan objek [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) yang digunakan untuk resolusi namespace.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Sebuah objek yang mengimplementasikan antarmuka [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) untuk digunakan dalam resolusi namespace. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* Kelas [XPathExpression](../)
* Kelas [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Ruang Nama [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)