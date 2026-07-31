---
title: CloneNode()
second_title: Aspose.Slides untuk Referensi API C++
description: Membuat duplikat dari node ini. Node Notasi tidak dapat digandakan. Memanggil metode ini pada objek XmlNotation akan melempar pengecualian.
type: docs
weight: 118
url: /id/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) metode


Membuat duplikat dari node ini. Node Notasi tidak dapat digandakan. Memanggil metode ini pada objek [XmlNotation](../) akan melempar pengecualian.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** untuk menggandakan secara rekursif subtree di bawah node yang ditentukan; **false** untuk menggandakan hanya node itu sendiri. |

### Nilai Kembalian

Sebuah [XmlNode](../../xmlnode/) salinan dari node yang memanggil metode ini.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNode](../../xmlnode/)
* Kelas [XmlNotation](../)
* Namespace [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)