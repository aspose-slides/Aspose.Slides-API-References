---
title: ValidateElement()
second_title: Referensi API Aspose.Slides untuk C++
description: Memvalidasi elemen dalam konteks saat ini.
type: docs
weight: 131
url: /id/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) metode

Memvalidasi elemen dalam konteks saat ini.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Nama lokal elemen yang akan divalidasi. |
| namespaceUri | const [String](../../../system/string/)\& | URI namespace elemen yang akan divalidasi. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Objek [XmlSchemaInfo](../../xmlschemainfo/) yang propertinya diatur setelah validasi nama elemen berhasil. Parameter ini dapat berupa **nullptr**. |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) metode

Memvalidasi elemen dalam konteks saat ini dengan nilai atribut **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation**, dan **xsi:NoNamespaceSchemaLocation** yang ditentukan.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Nama lokal elemen yang akan divalidasi. |
| namespaceUri | const [String](../../../system/string/)\& | URI namespace elemen yang akan divalidasi. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Objek [XmlSchemaInfo](../../xmlschemainfo/) yang propertinya diatur setelah validasi nama elemen berhasil. Parameter ini dapat berupa **nullptr**. |
| xsiType | const [String](../../../system/string/)\& | Nilai atribut **xsi:Type** dari elemen. Parameter ini dapat berupa **nullptr**. |
| xsiNil | const [String](../../../system/string/)\& | Nilai atribut **xsi:Nil** dari elemen. Parameter ini dapat berupa **nullptr**. |
| xsiSchemaLocation | const [String](../../../system/string/)\& | Nilai atribut **xsi:SchemaLocation** dari elemen. Parameter ini dapat berupa **nullptr**. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | Nilai atribut **xsi:NoNamespaceSchemaLocation** dari elemen. Parameter ini dapat berupa **nullptr**. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [XmlSchemaInfo](../../xmlschemainfo/)
* Kelas [XmlSchemaValidator](../)
* Ruang Nama [System::Xml::Schema](../../)
* Pustaka [Aspose.Slides](../../../)