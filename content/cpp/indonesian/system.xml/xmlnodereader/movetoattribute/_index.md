---
title: MoveToAttribute()
second_title: Referensi API Aspose.Slides untuk C++
description: Berpindah ke atribut dengan nama yang ditentukan.
type: docs
weight: 300
url: /id/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) metode

Berpindah ke atribut dengan nama yang ditentukan.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama yang memenuhi syarat dari atribut. |

### Nilai Kembali

**true** jika atribut ditemukan; jika tidak, **false**. Jika **false**, posisi pembaca tidak berubah.

## XmlNodeReader::MoveToAttribute(String, String) metode

Berpindah ke atribut dengan nama lokal dan URI ruang nama yang ditentukan.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama lokal dari atribut. |
| namespaceURI | [String](../../../system/string/) | URI ruang nama dari atribut. |

### Nilai Kembali

**true** jika atribut ditemukan; jika tidak, **false**. Jika **false**, posisi pembaca tidak berubah.

## XmlNodeReader::MoveToAttribute(int32_t) metode

Berpindah ke atribut dengan indeks yang ditentukan.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| attributeIndex | **int32_t** | Indeks atribut. |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlNodeReader](../)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)