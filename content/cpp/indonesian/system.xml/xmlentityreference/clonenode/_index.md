---
title: CloneNode()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat duplikat dari node ini.
type: docs
weight: 92
url: /id/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) method


Membuat duplikat dari node ini.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| deep | **bool** | **true** untuk menyalin secara rekursif subtree di bawah node yang ditentukan; **false** untuk menyalin hanya node itu sendiri. Untuk node [XmlEntityReference](../), metode ini selalu mengembalikan node referensi entitas tanpa anak. Teks pengganti diatur ketika node disisipkan ke dalam induk. |

### Nilai Kembali

Node yang disalin.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNode](../../xmlnode/)
* Kelas [XmlEntityReference](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)