---
title: ReadElementContentAs()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca konten elemen sebagai tipe yang diminta.
type: docs
weight: 586
url: /id/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metode

Membaca isi elemen sebagai tipe yang diminta.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Tipe nilai yang akan dikembalikan. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Objek [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) yang digunakan untuk menyelesaikan setiap prefiks namespace yang terkait dengan konversi tipe. |

### Nilai Kembali

Konten elemen yang dikonversi menjadi objek bertipe yang diminta.

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) metode

Memeriksa bahwa nama lokal dan URI namespace yang ditentukan cocok dengan elemen saat ini, kemudian membaca konten elemen sebagai tipe yang diminta.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Tipe nilai yang akan dikembalikan. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Objek [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) yang digunakan untuk menyelesaikan setiap prefiks namespace yang terkait dengan konversi tipe. |
| localName | [String](../../../system/string/) | Nama lokal elemen. |
| namespaceURI | [String](../../../system/string/) | URI namespace elemen. |

### Nilai Kembali

Konten elemen yang dikonversi menjadi objek bertipe yang diminta.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)