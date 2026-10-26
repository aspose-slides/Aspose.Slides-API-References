---
title: CreateAttribute()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah XmlAttribute dengan nama yang ditentukan.
type: docs
weight: 274
url: /id/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) metode


Membuat sebuah [XmlAttribute](../../xmlattribute/) dengan nama yang ditentukan.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nama yang memenuhi syarat dari atribut. Jika nama mengandung titik dua, nilai [XmlNode::get_Prefix](../../xmlnode/get_prefix/) mencerminkan bagian nama sebelum titik dua pertama dan nilai [XmlDocument::get_LocalName](../get_localname/) mencerminkan bagian nama setelah titik dua pertama. [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) tetap kosong kecuali awalan adalah awalan bawaan yang dikenali seperti **xmlns**. Dalam kasus ini get_NamespaceURI memiliki nilai [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Nilai Kembalian

[XmlAttribute](../../xmlattribute/) baru.

## XmlDocument::CreateAttribute(const String\&, const String\&) metode


Membuat sebuah [XmlAttribute](../../xmlattribute/) dengan nama yang memenuhi syarat dan [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) yang ditentukan.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | Nama yang memenuhi syarat dari atribut. Jika nama mengandung titik dua maka nilai [XmlNode::get_Prefix](../../xmlnode/get_prefix/) akan mencerminkan bagian nama sebelum titik dua dan nilai [XmlDocument::get_LocalName](../get_localname/) akan mencerminkan bagian nama setelah titik dua. |
| namespaceURI | const [String](../../../system/string/)\& | namespaceURI dari atribut. Jika nama yang memenuhi syarat menyertakan awalan **xmlns**, maka parameter ini harus [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Nilai Kembalian

[XmlAttribute](../../xmlattribute/) baru.

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) metode


Membuat sebuah [XmlAttribute](../../xmlattribute/) dengan [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/), dan [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) yang ditentukan.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Awalan dari atribut (jika ada). [String::Empty](../../../system/string/empty/) dan **nullptr** bersifat ekivalen. |
| localName | const [String](../../../system/string/)\& | Nama lokal dari atribut. |
| namespaceURI | const [String](../../../system/string/)\& | URI ruang nama dari atribut (jika ada). [String::Empty](../../../system/string/empty/) dan **nullptr** bersifat ekivalen. Jika **prefix** adalah **xmlns**, maka parameter ini harus [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;) jika tidak, sebuah pengecualian akan dilempar. |

### Nilai Kembalian

[XmlAttribute](../../xmlattribute/) baru.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlAttribute](../../xmlattribute/)
* Kelas [String](../../../system/string/)
* Kelas [XmlDocument](../)
* Ruang Nama [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)