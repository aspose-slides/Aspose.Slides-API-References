---
title: AddNamespace()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan namespace yang diberikan ke koleksi.
type: docs
weight: 66
url: /id/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) metode

Menambahkan namespace yang diberikan ke koleksi.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Awalan yang akan dikaitkan dengan namespace yang ditambahkan. Gunakan [String::Empty](../../../system/string/empty/) untuk menambahkan namespace default. Jika [XmlNamespaceManager](../) akan digunakan untuk menyelesaikan namespace dalam ekspresi XML Path Language ([XPath](../../../system.xml.xpath/)), awalan harus ditentukan. Jika suatu ekspresi [XPath](../../../system.xml.xpath/) tidak menyertakan awalan, diasumsikan bahwa Uniform Resource Identifier (URI) namespace adalah namespace kosong. Untuk informasi lebih lanjut tentang ekspresi [XPath](../../../system.xml.xpath/) dan [XmlNamespaceManager](../), lihat metode XmlNode::SelectNodes(String) dan XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>). |
| uri | [String](../../../system/string/) | Namespace yang akan ditambahkan. |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)