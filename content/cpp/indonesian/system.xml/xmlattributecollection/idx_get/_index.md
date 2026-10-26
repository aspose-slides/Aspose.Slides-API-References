---
title: idx_get()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan atribut dengan indeks yang ditentukan.
type: docs
weight: 1
url: /id/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) method


Mengembalikan atribut dengan indeks yang ditentukan.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | Indeks atribut. |

### Nilai Kembali

Atribut pada indeks yang ditentukan.

## XmlAttributeCollection::idx_get(const String\&) method


Mengembalikan atribut dengan nama yang ditentukan.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nama lengkap atribut. |

### Nilai Kembali

Atribut dengan nama yang ditentukan. Jika atribut tidak ada, metode ini mengembalikan **nullptr**.

## XmlAttributeCollection::idx_get(const String\&, const String\&) method


Mengembalikan atribut dengan nama lokal dan Uniform Resource Identifier (URI) ruang nama yang ditentukan.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Nama lokal atribut. |
| namespaceURI | const [String](../../../system/string/)\& | URI ruang nama atribut. |

### Nilai Kembali

Atribut dengan nama lokal dan URI ruang nama yang ditentukan. Jika atribut tidak ada, metode ini mengembalikan **nullptr**.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlAttribute](../../xmlattribute/)
* Kelas [XmlAttributeCollection](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)