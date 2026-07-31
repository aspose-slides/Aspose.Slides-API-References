---
title: CloneNode()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat duplikat node ini.
type: docs
weight: 53
url: /id/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) metode

Membuat duplikat node ini.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| deep | **bool** | **true** untuk secara rekursif mengkloning subpohon di bawah node yang ditentukan; **false** untuk mengkloning hanya node itu sendiri. Karena node CDATA tidak memiliki anak, terlepas dari pengaturan parameter, node yang dikloning akan selalu menyertakan konten data. |

### Nilai Kembalian

Node yang dikloning.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNode](../../xmlnode/)
* Kelas [XmlCDataSection](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)