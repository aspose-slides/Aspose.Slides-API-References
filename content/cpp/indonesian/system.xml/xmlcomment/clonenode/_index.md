---
title: CloneNode()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat duplikat node ini.
type: docs
weight: 40
url: /id/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) metode


Membuat duplikat node ini.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```


### Argument

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| deep | **bool** | **true** untuk secara rekursif menggandakan subtree di bawah node yang ditentukan; **false** untuk menggandakan hanya node itu sendiri. Karena node komentar tidak memiliki anak, node yang digandakan selalu menyertakan konten teks, terlepas dari pengaturan parameter. |

### Nilai Kembalian

Node yang digandakan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNode](../../xmlnode/)
* Kelas [XmlComment](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)