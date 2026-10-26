---
title: ReadContentAs()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca konten sebagai objek dari tipe yang ditentukan.
type: docs
weight: 456
url: /id/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metode

Membaca konten sebagai objek dari tipe yang ditentukan.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Tipe nilai yang akan dikembalikan. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Sebuah objek [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) yang digunakan untuk menyelesaikan setiap prefiks namespace yang terkait dengan konversi tipe. Sebagai contoh, ini dapat digunakan saat mengonversi objek [XmlQualifiedName](../../xmlqualifiedname/) menjadi **xs:string**. Nilai ini dapat **nullptr**. |

### Nilai Kembalian

Konten teks yang digabungkan atau nilai atribut yang dikonversi ke tipe yang diminta.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [TypeInfo](../../../system/typeinfo/)
* Kelas [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Kelas [XmlReader](../)
* Namespace [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)