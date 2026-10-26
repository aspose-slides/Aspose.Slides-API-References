---
title: XmlSchemaValidator()
second_title: Referensi API Aspose.Slides untuk C++
description: Menginisialisasi sebuah instance baru dari kelas XmlSchemaValidator.
type: docs
weight: 92
url: /id/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) konstruktor

Menginisialisasi sebuah instance baru dari kelas [XmlSchemaValidator](../).

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | Sebuah objek [XmlNameTable](../../../system.xml/xmlnametable/) yang berisi nama elemen dan atribut sebagai string yang diatomisasi. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | Sebuah objek [XmlSchemaSet](../../xmlschemaset/) yang berisi skema XML [Schema](../../) Definition Language (XSD) yang digunakan untuk validasi. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Sebuah objek [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) yang digunakan untuk menyelesaikan namespace yang ditemui selama validasi. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | Sebuah nilai XmlSchemaValidationFlags yang menentukan opsi validasi skema. |

## Lihat Juga

* Enum [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNameTable](../../../system.xml/xmlnametable/)
* Kelas [XmlSchemaSet](../../xmlschemaset/)
* Kelas [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Kelas [XmlSchemaValidator](../)
* Ruang nama [System::Xml::Schema](../../)
* Perpustakaan [Aspose.Slides](../../../)