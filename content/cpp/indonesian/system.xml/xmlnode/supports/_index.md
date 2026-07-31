---
title: Supports()
second_title: Referensi API Aspose.Slides untuk C++
description: Menguji apakah implementasi DOM mengimplementasikan fitur tertentu.
type: docs
weight: 482
url: /id/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) metode


Menguji apakah implementasi DOM mendukung fitur tertentu.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| feature | [String](../../../system/string/) | Nama paket dari fitur yang akan diuji. Nama ini tidak peka huruf besar/kecil. |
| version | [String](../../../system/string/) | Nomor versi dari nama paket yang akan diuji. Jika versi tidak ditentukan (null), mendukung versi apa pun dari fitur menyebabkan metode mengembalikan true. |

### Nilai Kembali

**true** jika fitur diimplementasikan pada versi yang ditentukan; jika tidak, **false**.
## Keterangan



Tabel berikut menggambarkan kombinasi yang menghasilkan **true**. 

| Feature | [Version](../../../system/version/)|
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |


## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlNode](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)