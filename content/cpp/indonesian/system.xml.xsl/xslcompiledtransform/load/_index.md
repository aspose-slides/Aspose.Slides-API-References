---
title: Load()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyusun lembar gaya yang terdapat dalam XmlReader.
type: docs
weight: 27
url: /id/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) method

Menyusun lembar gaya yang terdapat dalam [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Sebuah [XmlReader](../../../system.xml/xmlreader/) yang berisi lembar gaya. |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) method

Menyusun lembar gaya XSLT yang terdapat dalam [XmlReader](../../../system.xml/xmlreader/). [XmlResolver](../../../system.xml/xmlresolver/) menyelesaikan setiap elemen **import** atau **include** XSLT dan pengaturan XSLT menentukan izin untuk lembar gaya.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) yang berisi lembar gaya. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | [XsltSettings](../../xsltsettings/) yang diterapkan pada lembar gaya. Jika ini **nullptr**, pengaturan [XsltSettings::get_Default](../../xsltsettings/get_default/) diterapkan. |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk menyelesaikan setiap lembar gaya yang direferensikan dalam elemen **import** dan **include** XSLT. Jika ini **nullptr**, sumber eksternal tidak diselesaikan. |

## XslCompiledTransform::Load(const String\&) method

Memuat dan menyusun lembar gaya yang terletak pada URI yang ditentukan.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | URI lembar gaya. |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) method

Memuat dan menyusun lembar gaya XSLT yang ditentukan oleh URI. [XmlResolver](../../../system.xml/xmlresolver/) menyelesaikan setiap elemen **import** atau **include** XSLT dan pengaturan XSLT menentukan izin untuk lembar gaya.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | URI lembar gaya. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | [XsltSettings](../../xsltsettings/) yang diterapkan pada lembar gaya. Jika ini **nullptr**, pengaturan [XsltSettings::get_Default](../../xsltsettings/get_default/) diterapkan. |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk menyelesaikan URI lembar gaya dan setiap lembar gaya yang direferensikan dalam elemen **import** dan **include** XSLT. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) method

Menyusun lembar gaya yang terdapat dalam objek IXPathNavigable.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objek yang mengimplementasikan antarmuka IXPathNavigable. Itu dapat berupa [XmlNode](../../../system.xml/xmlnode/) (biasanya sebuah [XmlDocument](../../../system.xml/xmldocument/)), atau XPathDocument yang berisi lembar gaya. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) method

Menyusun lembar gaya XSLT yang terdapat dalam IXPathNavigable. [XmlResolver](../../../system.xml/xmlresolver/) menyelesaikan setiap elemen **import** atau **include** XSLT dan pengaturan XSLT menentukan izin untuk lembar gaya.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objek yang mengimplementasikan antarmuka IXPathNavigable. Itu dapat berupa [XmlNode](../../../system.xml/xmlnode/) (biasanya sebuah [XmlDocument](../../../system.xml/xmldocument/)), atau XPathDocument yang berisi lembar gaya. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | [XsltSettings](../../xsltsettings/) yang diterapkan pada lembar gaya. Jika ini **nullptr**, pengaturan [XsltSettings::get_Default](../../xsltsettings/get_default/) diterapkan. |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk menyelesaikan setiap lembar gaya yang direferensikan dalam elemen **import** dan **include** XSLT. Jika ini **nullptr**, sumber eksternal tidak diselesaikan. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslCompiledTransform](../)
* Class [XsltSettings](../../xsltsettings/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [String](../../../system/string/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)