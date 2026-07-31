---
title: XmlSeverityType
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili tingkat keparahan peristiwa validasi.
type: docs
weight: 1080
url: /id/system.xml.schema/xmlseveritytype/
---
## XmlSeverityType enum

Mewakili tingkat keparahan dari peristiwa validasi.

```cpp
enum class XmlSeverityType
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Error | 0 | Menunjukkan bahwa terjadi error validasi saat memvalidasi dokumen instance. Ini berlaku untuk definisi tipe dokumen (DTDs) dan bahasa definisi XML [Schema](../) (XSD). Konsorsium World Wide [Web](../../system.web/) (W3C) mempertimbangkan kendala validitas sebagai error. Jika tidak ada handler peristiwa validasi yang dibuat, error akan melempar pengecualian. |
| Warning | 1 | Menunjukkan bahwa peristiwa validasi terjadi yang bukan merupakan error. Peringatan biasanya dikeluarkan ketika tidak ada DTD, atau XML [Schema](../) untuk memvalidasi elemen atau atribut tertentu. Tidak seperti error, peringatan tidak melempar pengecualian jika tidak ada handler peristiwa validasi. |

## Lihat Juga

* Ruang Nama [System::Xml::Schema](../)
* Pustaka [Aspose.Slides](../../)