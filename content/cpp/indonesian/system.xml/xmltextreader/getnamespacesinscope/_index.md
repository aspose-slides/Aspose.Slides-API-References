---
title: GetNamespacesInScope()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan koleksi yang berisi semua namespace yang saat ini berada dalam lingkup.
type: docs
weight: 716
url: /id/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) metode


Mengembalikan koleksi yang berisi semua namespace yang saat ini berada dalam lingkup.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Nilai XmlNamespaceScope yang menentukan jenis node namespace yang akan dikembalikan. |

### Nilai Kembali

Objek IDictionary yang berisi semua namespace yang saat ini berada dalam lingkup. Jika pembaca tidak berada pada sebuah elemen, kamus kosong (tanpa namespace) dikembalikan.

## Lihat Juga

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)