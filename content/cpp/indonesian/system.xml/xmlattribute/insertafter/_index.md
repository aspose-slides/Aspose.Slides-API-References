---
title: InsertAfter()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyisipkan node yang ditentukan tepat setelah node referensi yang ditentukan.
type: docs
weight: 222
url: /id/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) method

Menyisipkan node yang ditentukan tepat setelah node referensi yang ditentukan.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) yang akan disisipkan. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/) yang merupakan node referensi. **newChild** ditempatkan setelah **refChild**. |

### Nilai Kembalian

[XmlNode](../../xmlnode/) yang disisipkan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNode](../../xmlnode/)
* Kelas [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)