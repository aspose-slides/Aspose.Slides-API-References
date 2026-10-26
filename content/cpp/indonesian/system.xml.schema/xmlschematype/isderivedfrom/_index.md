---
title: IsDerivedFrom()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengembalikan nilai yang menunjukkan apakah tipe skema turunan yang ditentukan diturunkan dari tipe skema dasar yang ditentukan.
type: docs
weight: 209
url: /id/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) metode

Mengembalikan nilai yang menunjukkan apakah tipe skema turunan yang ditentukan diturunkan dari tipe skema dasar yang ditentukan.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | [XmlSchemaType](../) turunan yang akan diuji. |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | [XmlSchemaType](../) dasar untuk menguji [XmlSchemaType](../) turunan terhadapnya. |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | Salah satu nilai XmlSchemaDerivationMethod yang mewakili metode derivasi tipe yang dikecualikan dari pengujian. |

### Nilai Kembali

**true** jika tipe turunan diturunkan dari tipe dasar; jika tidak, **false**.

## Lihat Juga

* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlSchemaType](../)
* Ruang Nama [System::Xml::Schema](../../)
* Perpustakaan [Aspose.Slides](../../../)