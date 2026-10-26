---
title: MoveToAttribute()
second_title: Aspose.Slides untuk Referensi API C++
description: Berpindah ke atribut dengan nama yang ditentukan.
type: docs
weight: 456
url: /id/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) metode

Berpindah ke atribut dengan nama yang ditentukan.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama yang memenuhi syarat untuk atribut. |

### Nilai Kembalian

**true** jika atribut ditemukan; jika tidak, **false**. Jika **false**, posisi pembaca tidak berubah.

## XmlValidatingReader::MoveToAttribute(String, String) metode

Berpindah ke atribut dengan nama lokal dan Uniform Resource Identifier (URI) ruang nama yang ditentukan.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal atribut. |
| namespaceURI | [String](../../../system/string/) | URI ruang nama atribut. |

### Nilai Kembalian

**true** jika atribut ditemukan; jika tidak, **false**. Jika **false**, posisi pembaca tidak berubah.

## XmlValidatingReader::MoveToAttribute(int32_t) metode

Berpindah ke atribut dengan indeks yang ditentukan.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | **int32_t** | Indeks atribut. |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlValidatingReader](../)
* RuangNama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)