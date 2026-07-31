---
title: Compile()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengkompilasi Model Objek Skema XML (SOM) menjadi informasi skema untuk validasi. Digunakan untuk memeriksa struktur sintaksis dan semantik dari SOM yang dibangun secara programatik. Pemeriksaan validasi semantik dilakukan selama kompilasi.
type: docs
weight: 352
url: /id/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) metode

Mengkompilasi Model XML [Schema](../../)[Object](../../../system/object/) (SOM) menjadi informasi skema untuk validasi. Digunakan untuk memeriksa struktur sintaksis dan semantik dari SOM yang dibangun secara programatik. Pemeriksaan validasi semantik dilakukan selama kompilasi.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Penangkap peristiwa validasi yang menerima informasi tentang kesalahan validasi XML [Schema](../../). |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) metode

Mengkompilasi Model XML [Schema](../../)[Object](../../../system/object/) (SOM) menjadi informasi skema untuk validasi. Digunakan untuk memeriksa struktur sintaksis dan semantik dari SOM yang dibangun secara programatik. Pemeriksaan validasi semantik dilakukan selama kompilasi.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Penangkap peristiwa validasi yang menerima informasi tentang kesalahan validasi XML [Schema](../../). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk menyelesaikan ruang nama yang direferensikan dalam elemen **include** dan **import**. |

## Lihat Juga

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlSchema](../)
* Kelas [XmlResolver](../../../system.xml/xmlresolver/)
* RuangNama [System::Xml::Schema](../../)
* Pustaka [Aspose.Slides](../../../)