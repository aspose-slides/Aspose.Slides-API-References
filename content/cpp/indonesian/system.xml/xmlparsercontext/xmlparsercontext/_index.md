---
title: XmlParserContext()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menginisialisasi sebuah instance baru dari kelas XmlParserContext dengan nilai XmlNameTable, XmlNamespaceManager, xml:lang, dan xml:space yang ditentukan."
type: docs
weight: 261
url: /id/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) konstruktor


Menginisialisasi sebuah instance baru dari kelas [XmlParserContext](../) dengan [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), nilai **xml:lang**, dan **xml:space** yang ditentukan.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) yang digunakan untuk mengatomkan string. Jika ini **nullptr**, tabel nama yang digunakan untuk membangun **nsMgr** akan digunakan sebagai gantinya. Untuk informasi lebih lanjut tentang string yang diatomkan, lihat [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) yang digunakan untuk mencari informasi namespace, atau **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | Lingkup **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Nilai XmlSpace yang menunjukkan lingkup **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) konstruktor


Menginisialisasi sebuah instance baru dari kelas [XmlParserContext](../) dengan [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space**, dan enkoding.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) yang digunakan untuk mengatomkan string. Jika ini **nullptr**, tabel nama yang digunakan untuk membangun **nsMgr** akan digunakan sebagai gantinya. Untuk informasi lebih lanjut tentang string yang diatomkan, lihat [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) yang digunakan untuk mencari informasi namespace, atau **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | Lingkup **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Nilai XmlSpace yang menunjukkan lingkup **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Objek Encoding yang menunjukkan pengaturan enkoding. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) konstruktor


Menginisialisasi sebuah instance baru dari kelas [XmlParserContext](../) dengan [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), URI dasar, **xml:lang**, **xml:space**, dan nilai jenis dokumen.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) yang digunakan untuk mengatomkan string. Jika ini **nullptr**, tabel nama yang digunakan untuk membangun **nsMgr** akan digunakan sebagai gantinya. Untuk informasi lebih lanjut tentang string yang diatomkan, lihat [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) yang digunakan untuk mencari informasi namespace, atau **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Nama deklarasi tipe dokumen. |
| pubId | const [String](../../../system/string/)\& | Pengidentifikasi publik. |
| sysId | const [String](../../../system/string/)\& | Pengidentifikasi sistem. |
| internalSubset | const [String](../../../system/string/)\& | Subset DTD internal. Subset DTD digunakan untuk resolusi entitas, bukan untuk validasi dokumen. |
| baseURI | const [String](../../../system/string/)\& | URI dasar untuk fragmen XML (lokasi tempat fragmen dimuat). |
| xmlLang | const [String](../../../system/string/)\& | Lingkup **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Nilai XmlSpace yang menunjukkan lingkup **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) konstruktor


Menginisialisasi sebuah instance baru dari kelas [XmlParserContext](../) dengan [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), URI dasar, **xml:lang**, **xml:space**, enkoding, dan nilai jenis dokumen.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) yang digunakan untuk mengatomkan string. Jika ini **nullptr**, tabel nama yang digunakan untuk membangun **nsMgr** akan digunakan sebagai gantinya. Untuk informasi lebih lanjut tentang string yang diatomkan, lihat [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) yang digunakan untuk mencari informasi namespace, atau **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Nama deklarasi tipe dokumen. |
| pubId | const [String](../../../system/string/)\& | Pengidentifikasi publik. |
| sysId | const [String](../../../system/string/)\& | Pengidentifikasi sistem. |
| internalSubset | const [String](../../../system/string/)\& | Subset DTD internal. DTD digunakan untuk resolusi entitas, bukan untuk validasi dokumen. |
| baseURI | const [String](../../../system/string/)\& | URI dasar untuk fragmen XML (lokasi tempat fragmen dimuat). |
| xmlLang | const [String](../../../system/string/)\& | Lingkup **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Nilai XmlSpace yang menunjukkan lingkup **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Objek Encoding yang menunjukkan pengaturan enkoding. |

## Lihat Juga

* Enum [XmlSpace](../../xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Class [XmlParserContext](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)