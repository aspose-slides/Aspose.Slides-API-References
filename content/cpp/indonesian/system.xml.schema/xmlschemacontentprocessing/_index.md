---
title: XmlSchemaContentProcessing
second_title: Referensi API Aspose.Slides untuk C++
description: Memberikan informasi tentang mode validasi penggantian elemen any dan anyAttribute.
type: docs
weight: 976
url: /id/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enum

Menyediakan informasi tentang mode validasi penggantian elemen **any** dan **anyAttribute**.

```cpp
enum class XmlSchemaContentProcessing
```

### Values

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | 0 | Item dokumen tidak divalidasi. |
| Skip | 1 | Item dokumen harus berupa XML yang terbentuk dengan baik dan tidak divalidasi oleh skema. |
| Lax | 2 | Jika skema yang terkait ditemukan, item dokumen akan divalidasi. Tidak ada kesalahan yang akan dilemparkan sebaliknya. |
| Strict | 3 | Pemroses skema harus menemukan skema yang terkait dengan namespace yang ditunjukkan untuk memvalidasi item dokumen. |

## Lihat Juga

* Namespace [System::Xml::Schema](../)
* Library [Aspose.Slides](../../)