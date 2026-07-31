---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan skema yang terletak pada URL yang diberikan ke dalam koleksi skema.
type: docs
weight: 40
url: /id/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) metode


Menambahkan skema yang terletak pada URL yang diberikan ke dalam koleksi skema.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI namespace yang terkait dengan skema. Untuk XML Schemas, biasanya ini adalah **targetNamespace**. |
| uri | const [String](../../../system/string/)\& | URL yang menentukan skema yang akan dimuat. |

### Nilai Kembali

[XmlSchema](../../xmlschema/) yang ditambahkan ke koleksi skema; **nullptr** jika skema yang ditambahkan adalah skema XDR atau jika terdapat kesalahan kompilasi dalam skema.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) metode


Menambahkan skema yang terdapat dalam [XmlReader](../../../system.xml/xmlreader/) ke koleksi skema.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI namespace yang terkait dengan skema. Untuk XML Schemas, biasanya ini adalah **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) yang berisi skema yang akan ditambahkan. |

### Nilai Kembali

[XmlSchema](../../xmlschema/) yang ditambahkan ke koleksi skema; **nullptr** jika skema yang ditambahkan adalah skema XDR atau jika terdapat kesalahan kompilasi dalam skema.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metode


Menambahkan skema yang terdapat dalam [XmlReader](../../../system.xml/xmlreader/) ke koleksi skema. [XmlResolver](../../../system.xml/xmlresolver/) yang ditentukan digunakan untuk menyelesaikan sumber eksternal apa pun.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI namespace yang terkait dengan skema. Untuk XML Schemas, biasanya ini adalah **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) yang berisi skema yang akan ditambahkan. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk menyelesaikan namespace yang direferensikan dalam elemen **include** dan **import** atau atribut **x-schema** (skema XDR). Jika ini **nullptr**, referensi eksternal tidak diselesaikan. |

### Nilai Kembali

[XmlSchema](../../xmlschema/) yang ditambahkan ke koleksi skema; **nullptr** jika skema yang ditambahkan adalah skema XDR atau jika terdapat kesalahan kompilasi dalam skema.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) metode


Menambahkan [XmlSchema](../../xmlschema/) ke koleksi.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) yang akan ditambahkan ke koleksi. |

### Nilai Kembali

Objek [XmlSchema](../../xmlschema/).

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metode


Menambahkan [XmlSchema](../../xmlschema/) ke koleksi. [XmlResolver](../../../system.xml/xmlresolver/) yang ditentukan digunakan untuk menyelesaikan referensi eksternal apa pun.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) yang akan ditambahkan ke koleksi. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) yang digunakan untuk menyelesaikan namespace yang direferensikan dalam elemen **include** dan **import**. Jika ini **nullptr**, referensi eksternal tidak diselesaikan. |

### Nilai Kembali

[XmlSchema](../../xmlschema/) yang ditambahkan ke koleksi skema.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) metode


Menambahkan semua namespace yang didefinisikan dalam koleksi yang diberikan (termasuk skema terkait) ke dalam koleksi ini.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | [XmlSchemaCollection](../) yang ingin Anda tambahkan ke koleksi ini. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlSchema](../../xmlschema/)
* Kelas [String](../../../system/string/)
* Kelas [XmlSchemaCollection](../)
* Kelas [XmlReader](../../../system.xml/xmlreader/)
* Kelas [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)