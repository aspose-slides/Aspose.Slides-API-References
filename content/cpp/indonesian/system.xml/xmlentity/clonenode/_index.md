---
title: CloneNode()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat duplikat dari node ini. Node entitas tidak dapat dikloning. Memanggil metode ini pada objek XmlEntity akan melempar pengecualian.
type: docs
weight: 170
url: /id/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) metode

Membuat duplikat dari node ini. Node entitas tidak dapat dikloning. Memanggil metode ini pada objek [XmlEntity](../) akan melempar pengecualian.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| deep | **bool** | **true** untuk mengkloning secara rekursif subtree di bawah node yang ditentukan; **false** untuk mengkloning hanya node itu sendiri. |

### Nilai Kembali

Sebuah salinan dari [XmlNode](../../xmlnode/) tempat metode ini dipanggil.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNode](../../xmlnode/)
* Kelas [XmlEntity](../)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)