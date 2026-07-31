---
title: Transform()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengubah data XML dalam XPathNavigator menggunakan args yang ditentukan dan menghasilkan hasil ke XmlReader.
type: docs
weight: 40
url: /id/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Mengubah data XML dalam XPathNavigator menggunakan **args** yang ditentukan dan mengeluarkan hasil ke [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Sebuah XPathNavigator yang berisi data yang akan diubah. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Sebuah [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen yang memiliki namespace dan digunakan sebagai masukan untuk transformasi. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk menyelesaikan fungsi XSLT **document()**. Jika ini **nullptr**, fungsi **document()** tidak diselesaikan. [XmlResolver](../../../system.xml/xmlresolver/) tidak disimpan dalam cache setelah metode ini selesai. |

### Nilai Kembali

Sebuah [XmlReader](../../../system.xml/xmlreader/) yang berisi hasil transformasi.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) method


Mengubah data XML dalam XPathNavigator menggunakan **args** yang ditentukan dan mengeluarkan hasil ke [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Sebuah XPathNavigator yang berisi data yang akan diubah. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Sebuah [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen yang memiliki namespace dan digunakan sebagai masukan untuk transformasi. |

### Nilai Kembali

Sebuah [XmlReader](../../../system.xml/xmlreader/) yang berisi hasil transformasi.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Mengubah data XML dalam XPathNavigator menggunakan args yang ditentukan dan mengeluarkan hasil ke [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Sebuah XPathNavigator yang berisi data yang akan diubah. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Sebuah [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen yang memiliki namespace dan digunakan sebagai masukan untuk transformasi. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) yang ingin Anda outputkan. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk menyelesaikan fungsi XSLT **document()**. Jika ini **nullptr**, fungsi **document()** tidak diselesaikan. [XmlResolver](../../../system.xml/xmlresolver/) tidak disimpan dalam cache setelah metode ini selesai. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Mengubah data XML dalam XPathNavigator menggunakan args yang ditentukan dan mengeluarkan hasil ke [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Sebuah XPathNavigator yang berisi data yang akan diubah. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Sebuah [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen yang memiliki namespace dan digunakan sebagai masukan untuk transformasi. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) yang ingin Anda outputkan. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Mengubah data XML dalam XPathNavigator menggunakan **args** yang ditentukan dan mengeluarkan hasil ke Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Sebuah XPathNavigator yang berisi data yang akan diubah. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Sebuah [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen yang memiliki namespace dan digunakan sebagai masukan untuk transformasi. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream yang ingin Anda outputkan. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk menyelesaikan fungsi XSLT **document()**. Jika ini **nullptr**, fungsi **document()** tidak diselesaikan. [XmlResolver](../../../system.xml/xmlresolver/) tidak disimpan dalam cache setelah metode ini selesai. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Mengubah data XML dalam XPathNavigator menggunakan **args** yang ditentukan dan mengeluarkan hasil ke Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Sebuah XPathNavigator yang berisi data yang akan diubah. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Sebuah [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen yang memiliki namespace dan digunakan sebagai masukan untuk transformasi. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream yang ingin Anda outputkan. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Mengubah data XML dalam XPathNavigator menggunakan **args** yang ditentukan dan mengeluarkan hasil ke TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Sebuah XPathNavigator yang berisi data yang akan diubah. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Sebuah [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen yang memiliki namespace dan digunakan sebagai masukan untuk transformasi. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter yang ingin Anda outputkan. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk menyelesaikan fungsi XSLT **document()**. Jika ini **nullptr**, fungsi **document()** tidak diselesaikan. [XmlResolver](../../../system.xml/xmlresolver/) tidak disimpan dalam cache setelah metode ini selesai. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Mengubah data XML dalam XPathNavigator menggunakan **args** yang ditentukan dan mengeluarkan hasil ke TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Sebuah XPathNavigator yang berisi data yang akan diubah. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Sebuah [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen yang memiliki namespace dan digunakan sebagai masukan untuk transformasi. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter yang ingin Anda outputkan. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Mengubah data XML dalam IXPathNavigable menggunakan **args** yang ditentukan dan mengeluarkan hasil ke [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Sebuah objek yang mengimplementasikan antarmuka IXPathNavigable. Itu dapat berupa [XmlNode](../../../system.xml/xmlnode/) (biasanya [XmlDocument](../../../system.xml/xmldocument/)), atau XPathDocument yang berisi data yang akan diubah. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Sebuah [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen yang memiliki namespace dan digunakan sebagai masukan untuk transformasi. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk menyelesaikan fungsi XSLT **document()**. Jika ini **nullptr**, fungsi **document()** tidak diselesaikan. [XmlResolver](../../../system.xml/xmlresolver/) tidak disimpan dalam cache setelah metode ini selesai. |

### Nilai Kembali

Sebuah [XmlReader](../../../system.xml/xmlreader/) yang berisi hasil transformasi.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) method


Mengubah data XML dalam IXPathNavigable menggunakan **args** yang ditentukan dan mengeluarkan hasil ke [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Sebuah objek yang mengimplementasikan antarmuka IXPathNavigable. Itu dapat berupa [XmlNode](../../../system.xml/xmlnode/) (biasanya [XmlDocument](../../../system.xml/xmldocument/)), atau XPathDocument yang berisi data yang akan diubah. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Sebuah [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen yang memiliki namespace dan digunakan sebagai masukan untuk transformasi. |

### Nilai Kembali

Sebuah [XmlReader](../../../system.xml/xmlreader/) yang berisi hasil transformasi.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Mengubah data XML dalam IXPathNavigable menggunakan **args** yang ditentukan dan mengeluarkan hasil ke TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Sebuah objek yang mengimplementasikan antarmuka IXPathNavigable. Itu dapat berupa [XmlNode](../../../system.xml/xmlnode/) (biasanya [XmlDocument](../../../system.xml/xmldocument/)), atau XPathDocument yang berisi data yang akan diubah. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Sebuah [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen yang memiliki namespace dan digunakan sebagai masukan untuk transformasi. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter yang ingin Anda outputkan. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk menyelesaikan fungsi XSLT **document()**. Jika ini **nullptr**, fungsi **document()** tidak diselesaikan. [XmlResolver](../../../system.xml/xmlresolver/) tidak disimpan dalam cache setelah metode ini selesai. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) method


Mengubah data XML dalam IXPathNavigable menggunakan **args** yang ditentukan dan mengeluarkan hasil ke TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Sebuah objek yang mengimplementasikan antarmuka IXPathNavigable. Itu dapat berupa [XmlNode](../../../system.xml/xmlnode/) (biasanya [XmlDocument](../../../system.xml/xmldocument/)), atau XPathDocument yang berisi data yang akan diubah. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Sebuah [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen yang memiliki namespace dan digunakan sebagai masukan untuk transformasi. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter yang ingin Anda outputkan. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Mengubah data XML dalam IXPathNavigable menggunakan **args** yang ditentukan dan mengeluarkan hasil ke Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Sebuah objek yang mengimplementasikan antarmuka IXPathNavigable. Itu dapat berupa [XmlNode](../../../system.xml/xmlnode/) (biasanya [XmlDocument](../../../system.xml/xmldocument/)), atau XPathDocument yang berisi data yang akan diubah. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Sebuah [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen yang memiliki namespace dan digunakan sebagai masukan untuk transformasi. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream yang ingin Anda outputkan. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk menyelesaikan fungsi XSLT **document()**. Jika ini **nullptr**, fungsi **document()** tidak diselesaikan. [XmlResolver](../../../system.xml/xmlresolver/) tidak disimpan dalam cache setelah metode [XslTransform::Transform](./) selesai. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) method


Mengubah data XML dalam IXPathNavigable menggunakan **args** yang ditentukan dan mengeluarkan hasil ke Stream.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Sebuah objek yang mengimplementasikan antarmuka IXPathNavigable. Itu dapat berupa [XmlNode](../../../system.xml/xmlnode/) (biasanya [XmlDocument](../../../system.xml/xmldocument/)), atau XPathDocument yang berisi data yang akan diubah. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Sebuah [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen yang memiliki namespace dan digunakan sebagai masukan untuk transformasi. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream yang ingin Anda outputkan. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Mengubah data XML dalam IXPathNavigable menggunakan **args** yang ditentukan dan mengeluarkan hasil ke [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Sebuah objek yang mengimplementasikan antarmuka IXPathNavigable. Itu dapat berupa [XmlNode](../../../system.xml/xmlnode/) (biasanya [XmlDocument](../../../system.xml/xmldocument/)), atau XPathDocument yang berisi data yang akan diubah. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Sebuah [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen yang memiliki namespace dan digunakan sebagai masukan untuk transformasi. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) yang ingin Anda outputkan. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk menyelesaikan fungsi XSLT **document()**. Jika ini **nullptr**, fungsi **document()** tidak diselesaikan. [XmlResolver](../../../system.xml/xmlresolver/) tidak disimpan dalam cache setelah metode ini selesai. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) method


Mengubah data XML dalam IXPathNavigable menggunakan **args** yang ditentukan dan mengeluarkan hasil ke [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Sebuah objek yang mengimplementasikan antarmuka IXPathNavigable. Itu dapat berupa [XmlNode](../../../system.xml/xmlnode/) (biasanya [XmlDocument](../../../system.xml/xmldocument/)), atau XPathDocument yang berisi data yang akan diubah. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Sebuah [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen yang memiliki namespace dan digunakan sebagai masukan untuk transformasi. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) yang ingin Anda outputkan. |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) method


Mengubah data XML dalam berkas masukan dan mengeluarkan hasil ke berkas keluaran.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | URL dokumen sumber yang akan diubah. |
| outputfile | const [String](../../../system/string/)\& | URL berkas keluaran. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk menyelesaikan fungsi XSLT **document()**. Jika ini **nullptr**, fungsi **document()** tidak diselesaikan. [XmlResolver](../../../system.xml/xmlresolver/) tidak disimpan dalam cache setelah metode [XslTransform::Transform](./) selesai. |

## XslTransform::Transform(const String\&, const String\&) method


Mengubah data XML dalam berkas masukan dan mengeluarkan hasil ke berkas keluaran.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | URL dokumen sumber yang akan diubah. |
| outputfile | const [String](../../../system/string/)\& | URL berkas keluaran. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlReader](../../../system.xml/xmlreader/)
* Kelas [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Kelas [XsltArgumentList](../../xsltargumentlist/)
* Kelas [XmlResolver](../../../system.xml/xmlresolver/)
* Kelas [XslTransform](../)
* Kelas [XmlWriter](../../../system.xml/xmlwriter/)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [TextWriter](../../../system.io/textwriter/)
* Kelas [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Kelas [String](../../../system/string/)
* Ruang Nama [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)