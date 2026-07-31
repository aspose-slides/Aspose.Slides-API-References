---
title: ValidateAttribute()
second_title: Referensi API Aspose.Slides untuk C++
description: Memvalidasi nama atribut, URI namespace, dan nilai dalam konteks elemen saat ini.
type: docs
weight: 144
url: /id/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) method


Memvalidasi nama atribut, URI namespace, dan nilai dalam konteks elemen saat ini.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Nama lokal atribut yang akan divalidasi. |
| namespaceUri | const [String](../../../system/string/)\& | URI namespace atribut yang akan divalidasi. |
| attributeValue | const [String](../../../system/string/)\& | Nilai atribut yang akan divalidasi. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Objek [XmlSchemaInfo](../../xmlschemainfo/) yang propertinya diatur setelah validasi atribut berhasil. Parameter ini dapat berupa **nullptr**. |

### Nilai Kembalian

Nilai atribut yang telah divalidasi.

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) method


Memvalidasi nama atribut, URI namespace, dan nilai dalam konteks elemen saat ini.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Nama lokal atribut yang akan divalidasi. |
| namespaceUri | const [String](../../../system/string/)\& | URI namespace atribut yang akan divalidasi. |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | Callback XmlValueGetter yang digunakan untuk memberikan nilai atribut dalam tipe yang kompatibel dengan tipe XML [Schema](../../) Definition Language (XSD) atribut. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Objek [XmlSchemaInfo](../../xmlschemainfo/) yang propertinya diatur setelah validasi atribut berhasil. Parameter ini dapat berupa **nullptr**. |

### Nilai Kembalian

Nilai atribut yang telah divalidasi.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Kelas [Object](../../../system/object/)
* Kelas [String](../../../system/string/)
* Kelas [XmlSchemaInfo](../../xmlschemainfo/)
* Kelas [XmlSchemaValidator](../)
* Ruang Nama [System::Xml::Schema](../../)
* Perpustakaan [Aspose.Slides](../../../)