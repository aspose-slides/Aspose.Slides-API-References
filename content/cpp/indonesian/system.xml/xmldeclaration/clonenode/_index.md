---
title: CloneNode()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat duplikat node ini.
type: docs
weight: 157
url: /id/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) metode

Membuat duplikat node ini.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| deep | **bool** | **true** untuk mengkloning secara rekursif subtree di bawah node yang ditentukan; **false** untuk mengkloning hanya node itu sendiri. Karena node [XmlDeclaration](../) tidak memiliki anak, node yang dikloning selalu menyertakan nilai data, terlepas dari pengaturan parameter. |

### Nilai Kembali

Node yang dikloning.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNode](../../xmlnode/)
* Kelas [XmlDeclaration](../)
* Ruang nama [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)