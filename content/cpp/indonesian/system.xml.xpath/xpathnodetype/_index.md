---
title: XPathNodeType
second_title: Referensi API Aspose.Slides untuk C++
description: Mendefinisikan tipe node XPath yang dapat dikembalikan dari kelas XPathNavigator.
type: docs
weight: 157
url: /id/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum

Mendefinisikan tipe node [XPath](../) yang dapat dikembalikan dari kelas [XPathNavigator](../xpathnavigator/).

```cpp
enum class XPathNodeType
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Root | 0 | Node akar dari dokumen XML atau pohon node. |
| Element | 1 | Sebuah elemen, seperti **<element>**. |
| Attribute | 2 | Sebuah atribut, seperti **id='123'**. |
| Namespace | 3 | Sebuah ruang nama, seperti **xmlns=\"namespace\"**. |
| Text | 4 | Konten teks dari sebuah node. Setara dengan Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) dan tipe node CDATA. Mengandung setidaknya satu karakter. |
| SignificantWhitespace | 5 | Sebuah node dengan karakter spasi putih dan **xml:space** diatur ke **preserve**. |
| Whitespace | 6 | Sebuah node yang hanya berisi karakter spasi putih dan tidak ada spasi putih yang signifikan. Karakter spasi putih adalah **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | Sebuah instruksi pemrosesan, seperti **<?pi test?>**. Ini tidak termasuk deklarasi XML, yang tidak terlihat oleh kelas [XPathNavigator](../xpathnavigator/). |
| Comment | 8 | Sebuah komentar, seperti ****. |
| All | 9 | Setiap tipe node XPathNodeType. |

## Lihat Juga

* Namespace [System::Xml::XPath](../)
* Library [Aspose.Slides](../../)