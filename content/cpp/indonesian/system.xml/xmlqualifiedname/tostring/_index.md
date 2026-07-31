---
title: ToString()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai string dari XmlQualifiedName.
type: docs
weight: 79
url: /id/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const metode

Mengembalikan nilai string dari [XmlQualifiedName](../).

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```

### Nilai Kembalian

Nilai string dari [XmlQualifiedName](../) dalam format **namespace:localname**. Jika objek tidak memiliki namespace yang ditetapkan, metode ini mengembalikan hanya nama lokal.

## XmlQualifiedName::ToString(const String\&, const String\&) metode

Mengembalikan nilai string dari [XmlQualifiedName](../).

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nama objek. |
| ns | const [String](../../../system/string/)\& | Namespace objek. |

### Nilai Kembalian

Nilai string dari [XmlQualifiedName](../) dalam format **namespace:localname**. Jika objek tidak memiliki namespace yang ditetapkan, metode ini mengembalikan hanya nama lokal.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlQualifiedName](../)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)