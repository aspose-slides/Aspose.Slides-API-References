---
title: SelectNodes()
second_title: Referensi API Aspose.Slides untuk C++
description: Memilih daftar node yang cocok dengan ekspresi XPath.
type: docs
weight: 365
url: /id/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) method

Memilih daftar node yang cocok dengan ekspresi [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Ekspresi [XPath](../../../system.xml.xpath/). |

### Nilai Kembali

Sebuah [XmlNodeList](../../xmlnodelist/) yang berisi kumpulan node yang cocok dengan kueri [XPath](../../../system.xml.xpath/).

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) method

Memilih daftar node yang cocok dengan ekspresi [XPath](../../../system.xml.xpath/). Prefiks apa pun yang ditemukan dalam ekspresi [XPath](../../../system.xml.xpath/) diselesaikan menggunakan [XmlNamespaceManager](../../xmlnamespacemanager/) yang disediakan.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Ekspresi [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Sebuah [XmlNamespaceManager](../../xmlnamespacemanager/) untuk digunakan dalam menyelesaikan namespace untuk prefiks dalam ekspresi [XPath](../../../system.xml.xpath/). |

### Nilai Kembali

Sebuah [XmlNodeList](../../xmlnodelist/) yang berisi kumpulan node yang cocok dengan kueri [XPath](../../../system.xml.xpath/).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)