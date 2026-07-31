---
title: Load()
second_title: Referensi API Aspose.Slides untuk C++
description: Memuat lembar gaya XSLT yang terdapat dalam XmlReader.
type: docs
weight: 27
url: /id/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) metode

Memuat lembar gaya XSLT yang terdapat dalam [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Objek [XmlReader](../../../system.xml/xmlreader/) yang berisi lembar gaya XSLT. |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metode

Memuat lembar gaya XSLT yang terdapat dalam [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Objek [XmlReader](../../../system.xml/xmlreader/) yang berisi lembar gaya XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk memuat lembar gaya apa pun yang dirujuk dalam elemen **xsl:import** dan **xsl:include**. Jika ini **nullptr**, sumber daya eksternal tidak diresolusikan. [XmlResolver](../../../system.xml/xmlresolver/) tidak di-cache setelah metode ini selesai. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) metode

Memuat lembar gaya XSLT yang terdapat dalam IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objek yang mengimplementasikan antarmuka IXPathNavigable. Itu dapat berupa [XmlNode](../../../system.xml/xmlnode/) (biasanya [XmlDocument](../../../system.xml/xmldocument/)), atau XPathDocument yang berisi lembar gaya XSLT. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metode

Memuat lembar gaya XSLT yang terdapat dalam IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Objek yang mengimplementasikan antarmuka IXPathNavigable. Itu dapat berupa [XmlNode](../../../system.xml/xmlnode/) (biasanya [XmlDocument](../../../system.xml/xmldocument/)), atau XPathDocument yang berisi lembar gaya XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk memuat lembar gaya apa pun yang dirujuk dalam elemen **xsl:import** dan **xsl:include**. Jika ini **nullptr**, sumber daya eksternal tidak diresolusikan. [XmlResolver](../../../system.xml/xmlresolver/) tidak di-cache setelah metode ini selesai. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) metode

Memuat lembar gaya XSLT yang terdapat dalam XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Objek XPathNavigator yang berisi lembar gaya XSLT. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metode

Memuat lembar gaya XSLT yang terdapat dalam XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Objek XPathNavigator yang berisi lembar gaya XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk memuat lembar gaya apa pun yang dirujuk dalam elemen **xsl:import** dan **xsl:include**. Jika ini **nullptr**, sumber daya eksternal tidak diresolusikan. [XmlResolver](../../../system.xml/xmlresolver/) tidak di-cache setelah metode ini selesai. |

## XslTransform::Load(const String\&) metode

Memuat lembar gaya XSLT yang ditentukan oleh URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL yang menentukan lembar gaya XSLT yang akan dimuat. |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metode

Memuat lembar gaya XSLT yang ditentukan oleh URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL yang menentukan lembar gaya XSLT yang akan dimuat. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk memuat lembar gaya dan lembar gaya apa pun yang dirujuk dalam elemen **xsl:import** dan **xsl:include**. Jika ini **nullptr**, [XmlUrlResolver](../../../system.xml/xmlurlresolver/) default tanpa kredensial pengguna digunakan untuk membuka lembar gaya. [XmlUrlResolver](../../../system.xml/xmlurlresolver/) default tidak digunakan untuk menyelesaikan sumber daya eksternal dalam lembar gaya, sehingga elemen **xsl:import** dan **xsl:include** tidak diselesaikan. [XmlResolver](../../../system.xml/xmlresolver/) tidak di-cache setelah metode ini selesai. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslTransform](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)