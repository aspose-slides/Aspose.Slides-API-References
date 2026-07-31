---
title: Transform()
second_title: Referensi API Aspose.Slides untuk C++
description: Menjalankan transformasi menggunakan dokumen input yang ditentukan oleh objek IXPathNavigable dan menghasilkan hasil ke sebuah XmlWriter.
type: docs
weight: 40
url: /id/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) metode


Menjalankan transformasi menggunakan dokumen input yang ditentukan oleh objek IXPathNavigable dan menghasilkan hasil ke sebuah [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Sebuah objek yang mengimplementasikan antarmuka IXPathNavigable. Itu dapat berupa [XmlNode](../../../system.xml/xmlnode/) (biasanya [XmlDocument](../../../system.xml/xmldocument/)), atau XPathDocument yang berisi data yang akan diubah. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) yang ingin Anda outputkan. Jika lembar gaya berisi elemen **xsl:output**, Anda harus membuat [XmlWriter](../../../system.xml/xmlwriter/) menggunakan objek [XmlWriterSettings](../../../system.xml/xmlwritersettings/) yang dikembalikan dari nilai [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Hal ini memastikan [XmlWriter](../../../system.xml/xmlwriter/) memiliki pengaturan output yang benar. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) metode


Menjalankan transformasi menggunakan dokumen input yang ditentukan oleh objek IXPathNavigable dan menghasilkan hasil ke sebuah [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) menyediakan argumen runtime tambahan.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Sebuah objek yang mengimplementasikan antarmuka IXPathNavigable. Itu dapat berupa [XmlNode](../../../system.xml/xmlnode/) (biasanya [XmlDocument](../../../system.xml/xmldocument/)), atau XPathDocument yang berisi data yang akan diubah. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen berkualifikasi namespace yang digunakan sebagai masukan untuk transformasi. Nilai ini dapat **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) yang ingin Anda outputkan. Jika lembar gaya berisi elemen **xsl:output**, Anda harus membuat [XmlWriter](../../../system.xml/xmlwriter/) menggunakan objek [XmlWriterSettings](../../../system.xml/xmlwritersettings/) yang dikembalikan dari nilai [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Hal ini memastikan [XmlWriter](../../../system.xml/xmlwriter/) memiliki pengaturan output yang benar. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) metode


Menjalankan transformasi menggunakan dokumen input yang ditentukan oleh objek IXPathNavigable dan menghasilkan hasil ke sebuah TextWriter. [XsltArgumentList](../../xsltargumentlist/) menyediakan argumen runtime tambahan.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Sebuah objek yang mengimplementasikan antarmuka IXPathNavigable. Itu dapat berupa [XmlNode](../../../system.xml/xmlnode/) (biasanya [XmlDocument](../../../system.xml/xmldocument/)), atau XPathDocument yang berisi data yang akan diubah. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen berkualifikasi namespace yang digunakan sebagai masukan untuk transformasi. Nilai ini dapat **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter yang ingin Anda outputkan. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) metode


Menjalankan transformasi menggunakan dokumen input yang ditentukan oleh objek IXPathNavigable dan menghasilkan hasil ke sebuah stream. [XsltArgumentList](../../xsltargumentlist/) menyediakan argumen runtime tambahan.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Sebuah objek yang mengimplementasikan antarmuka IXPathNavigable. Itu dapat berupa [XmlNode](../../../system.xml/xmlnode/) (biasanya [XmlDocument](../../../system.xml/xmldocument/)), atau XPathDocument yang berisi data yang akan diubah. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen berkualifikasi namespace yang digunakan sebagai masukan untuk transformasi. Nilai ini dapat **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream yang ingin Anda outputkan. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) metode


Menjalankan transformasi menggunakan dokumen input yang ditentukan oleh objek [XmlReader](../../../system.xml/xmlreader/) dan menghasilkan hasil ke sebuah [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) yang berisi dokumen input. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) yang ingin Anda outputkan. Jika lembar gaya berisi elemen **xsl:output**, Anda harus membuat [XmlWriter](../../../system.xml/xmlwriter/) menggunakan objek [XmlWriterSettings](../../../system.xml/xmlwritersettings/) yang dikembalikan dari nilai [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Hal ini memastikan [XmlWriter](../../../system.xml/xmlwriter/) memiliki pengaturan output yang benar. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) metode


Menjalankan transformasi menggunakan dokumen input yang ditentukan oleh objek [XmlReader](../../../system.xml/xmlreader/) dan menghasilkan hasil ke sebuah [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) menyediakan argumen runtime tambahan.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) yang berisi dokumen input. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen berkualifikasi namespace yang digunakan sebagai masukan untuk transformasi. Nilai ini dapat **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) yang ingin Anda outputkan. Jika lembar gaya berisi elemen **xsl:output**, Anda harus membuat [XmlWriter](../../../system.xml/xmlwriter/) menggunakan objek [XmlWriterSettings](../../../system.xml/xmlwritersettings/) yang dikembalikan dari nilai [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Hal ini memastikan [XmlWriter](../../../system.xml/xmlwriter/) memiliki pengaturan output yang benar. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) metode


Menjalankan transformasi menggunakan dokumen input yang ditentukan oleh objek [XmlReader](../../../system.xml/xmlreader/) dan menghasilkan hasil ke sebuah TextWriter. [XsltArgumentList](../../xsltargumentlist/) menyediakan argumen runtime tambahan.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) yang berisi dokumen input. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen berkualifikasi namespace yang digunakan sebagai masukan untuk transformasi. Nilai ini dapat **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter yang ingin Anda outputkan. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) metode


Menjalankan transformasi menggunakan dokumen input yang ditentukan oleh objek [XmlReader](../../../system.xml/xmlreader/) dan menghasilkan hasil ke sebuah stream. [XsltArgumentList](../../xsltargumentlist/) menyediakan argumen runtime tambahan.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) yang berisi dokumen input. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen berkualifikasi namespace yang digunakan sebagai masukan untuk transformasi. Nilai ini dapat **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream yang ingin Anda outputkan. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) metode


Menjalankan transformasi menggunakan dokumen input yang ditentukan oleh URI dan menghasilkan hasil ke sebuah [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI dari dokumen input. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) yang ingin Anda outputkan. Jika lembar gaya berisi elemen **xsl:output**, Anda harus membuat [XmlWriter](../../../system.xml/xmlwriter/) menggunakan objek [XmlWriterSettings](../../../system.xml/xmlwritersettings/) yang dikembalikan dari nilai [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Hal ini memastikan [XmlWriter](../../../system.xml/xmlwriter/) memiliki pengaturan output yang benar. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) metode


Menjalankan transformasi menggunakan dokumen input yang ditentukan oleh URI dan menghasilkan hasil ke sebuah [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) menyediakan argumen runtime tambahan.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI dari dokumen input. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen berkualifikasi namespace yang digunakan sebagai masukan untuk transformasi. Nilai ini dapat **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) yang ingin Anda outputkan. Jika lembar gaya berisi elemen **xsl:output**, Anda harus membuat [XmlWriter](../../../system.xml/xmlwriter/) menggunakan objek [XmlWriterSettings](../../../system.xml/xmlwritersettings/) yang dikembalikan dari nilai [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Hal ini memastikan [XmlWriter](../../../system.xml/xmlwriter/) memiliki pengaturan output yang benar. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) metode


Menjalankan transformasi menggunakan dokumen input yang ditentukan oleh URI dan menghasilkan hasil ke sebuah TextWriter.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI dari dokumen input. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen berkualifikasi namespace yang digunakan sebagai masukan untuk transformasi. Nilai ini dapat **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter yang ingin Anda outputkan. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) metode


Menjalankan transformasi menggunakan dokumen input yang ditentukan oleh URI dan menghasilkan hasil ke stream. [XsltArgumentList](../../xsltargumentlist/) menyediakan argumen runtime tambahan.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI dari dokumen input. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen berkualifikasi namespace yang digunakan sebagai masukan untuk transformasi. Nilai ini dapat **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream yang ingin Anda outputkan. |

## XslCompiledTransform::Transform(const String\&, const String\&) metode


Menjalankan transformasi menggunakan dokumen input yang ditentukan oleh URI dan menghasilkan hasil ke sebuah file.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | URI dari dokumen input. |
| resultsFile | const [String](../../../system/string/)\& | URI dari file output. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) metode


Menjalankan transformasi menggunakan dokumen input yang ditentukan oleh objek [XmlReader](../../../system.xml/xmlreader/) dan menghasilkan hasil ke sebuah [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) menyediakan argumen runtime tambahan dan [XmlResolver](../../../system.xml/xmlresolver/) menyelesaikan fungsi XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) yang berisi dokumen input. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | [XsltArgumentList](../../xsltargumentlist/) yang berisi argumen berkualifikasi namespace yang digunakan sebagai masukan untuk transformasi. Nilai ini dapat **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) yang ingin Anda outputkan. Jika lembar gaya berisi elemen **xsl:output**, Anda harus membuat [XmlWriter](../../../system.xml/xmlwriter/) menggunakan objek [XmlWriterSettings](../../../system.xml/xmlwritersettings/) yang dikembalikan dari nilai [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Hal ini memastikan [XmlWriter](../../../system.xml/xmlwriter/) memiliki pengaturan output yang benar. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk menyelesaikan fungsi XSLT **document()**. Jika ini **nullptr**, fungsi **document()** tidak diselesaikan. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) metode


Menjalankan transformasi dengan menggunakan dokumen input yang ditentukan oleh objek IXPathNavigable dan menghasilkan hasil ke sebuah [XmlWriter](../../../system.xml/xmlwriter/). [XsltArgumentList](../../xsltargumentlist/) menyediakan argumen runtime tambahan dan [XmlResolver](../../../system.xml/xmlresolver/) menyelesaikan fungsi XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Dokumen yang akan diubah yang ditentukan oleh objek IXPathNavigable. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Daftar argumen sebagai [XsltArgumentList](../../xsltargumentlist/). |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | [XmlWriter](../../../system.xml/xmlwriter/) yang ingin Anda outputkan. Jika lembar gaya berisi elemen **xsl:output**, Anda harus membuat [XmlWriter](../../../system.xml/xmlwriter/) dengan menggunakan objek [XmlWriterSettings](../../../system.xml/xmlwritersettings/) yang dikembalikan dari nilai [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Hal ini memastikan [XmlWriter](../../../system.xml/xmlwriter/) memiliki pengaturan output yang benar. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk menyelesaikan fungsi XSLT **document()**. Jika ini **nullptr**, fungsi **document()** tidak diselesaikan. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Kelas [XmlWriter](../../../system.xml/xmlwriter/)
* Kelas [XslCompiledTransform](../)
* Kelas [XsltArgumentList](../../xsltargumentlist/)
* Kelas [TextWriter](../../../system.io/textwriter/)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [XmlReader](../../../system.xml/xmlreader/)
* Kelas [String](../../../system/string/)
* Kelas [XmlResolver](../../../system.xml/xmlresolver/)
* Ruang nama [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)