---
title: CheckValidity()
second_title: Referensi API Aspose.Slides untuk C++
description: Memverifikasi bahwa data XML dalam XPathNavigator sesuai dengan bahasa definisi XML Schema (XSD) yang disediakan.
type: docs
weight: 755
url: /id/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) metode

Memverifikasi bahwa data XML dalam [XPathNavigator](../) sesuai dengan bahasa definisi XML [Schema](../../../system.xml.schema/) (XSD) yang disediakan.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | XmlSchemaSet yang berisi skema yang digunakan untuk memvalidasi data XML yang terdapat dalam [XPathNavigator](../). |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | ValidationEventHandler yang menerima informasi tentang peringatan dan kesalahan validasi skema. |

### Nilai Kembalian

**true** jika tidak ada kesalahan validasi skema; sebaliknya, **false**.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Kelas [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Kelas [XPathNavigator](../)
* Ruang Nama [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)