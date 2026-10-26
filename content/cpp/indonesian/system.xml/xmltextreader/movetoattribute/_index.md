---
title: MoveToAttribute()
second_title: Referensi API Aspose.Slides untuk C++
description: Berpindah ke atribut dengan nama yang ditentukan.
type: docs
weight: 508
url: /id/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) metode

Berpindah ke atribut dengan nama yang ditentukan.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama yang memenuhi syarat dari atribut. |

### Nilai Kembalian

**true** jika atribut ditemukan; jika tidak, **false**. Jika **false**, posisi pembaca tidak berubah.

## XmlTextReader::MoveToAttribute(String, String) metode

Berpindah ke atribut dengan nama lokal dan URI namespace yang ditentukan.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal dari atribut. |
| namespaceURI | [String](../../../system/string/) | URI namespace dari atribut. |

### Nilai Kembalian

**true** jika atribut ditemukan; jika tidak, **false**. Jika **false**, posisi pembaca tidak berubah.

## XmlTextReader::MoveToAttribute(int32_t) metode

Berpindah ke atribut dengan indeks yang ditentukan.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | **int32_t** | Indeks dari atribut. |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlTextReader](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)