---
title: XmlSchemaValidationFlags
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan opsi validasi skema yang digunakan oleh kelas XmlSchemaValidator dan XmlReader.
type: docs
weight: 1054
url: /id/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum

Menentukan opsi validasi skema yang digunakan oleh kelas [XmlSchemaValidator](../xmlschemavalidator/) dan [XmlReader](../../system.xml/xmlreader/).

```cpp
enum class XmlSchemaValidationFlags
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | 0 | Jangan proses batasan identitas, skema inline, petunjuk lokasi skema, atau laporkan peringatan validasi skema. |
| ProcessInlineSchema | 1 | Proses skema inline yang ditemui selama validasi. |
| ProcessSchemaLocation | 2 | Proses petunjuk lokasi skema (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**) yang ditemui selama validasi. |
| ReportValidationWarnings | 4 | Laporkan peringatan validasi skema yang ditemui selama validasi. |
| ProcessIdentityConstraints | 8 | Proses batasan identitas (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**) yang ditemui selama validasi. |
| AllowXmlAttributes | 16 | Izinkan atribut xml:* meskipun tidak didefinisikan dalam skema. Atribut akan divalidasi berdasarkan tipe datanya. |

## Lihat Juga

* Ruang nama [System::Xml::Schema](../)
* Pustaka [Aspose.Slides](../../)