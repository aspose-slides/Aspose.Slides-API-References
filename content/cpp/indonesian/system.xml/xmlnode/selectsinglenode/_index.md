---
title: SelectSingleNode()
second_title: Aspose.Slides untuk Referensi API C++
description: Memilih XmlNode pertama yang cocok dengan ekspresi XPath.
type: docs
weight: 352
url: /id/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) metode

Memilih [XmlNode](../) pertama yang cocok dengan ekspresi [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Ekspresi [XPath](../../../system.xml.xpath/). |

### Nilai Kembalian

[XmlNode](../) pertama yang cocok dengan kueri [XPath](../../../system.xml.xpath/) atau **nullptr** jika tidak ada node yang cocok ditemukan.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) metode

Memilih [XmlNode](../) pertama yang cocok dengan ekspresi [XPath](../../../system.xml.xpath/). Prefiks apa pun yang ditemukan dalam ekspresi [XPath](../../../system.xml.xpath/) diselesaikan menggunakan [XmlNamespaceManager](../../xmlnamespacemanager/) yang disediakan.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Ekspresi [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Sebuah [XmlNamespaceManager](../../xmlnamespacemanager/) untuk digunakan dalam menyelesaikan namespace untuk prefiks dalam ekspresi [XPath](../../../system.xml.xpath/). |

### Nilai Kembalian

[XmlNode](../) pertama yang cocok dengan kueri [XPath](../../../system.xml.xpath/) atau **nullptr** jika tidak ada node yang cocok ditemukan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNode](../)
* Kelas [String](../../../system/string/)
* Kelas [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)