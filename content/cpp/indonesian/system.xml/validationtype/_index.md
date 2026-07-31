---
title: ValidationType
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan jenis validasi yang akan dilakukan.
type: docs
weight: 729
url: /id/system.xml/validationtype/
---
## ValidationType enum

Menentukan jenis validasi yang akan dilakukan.

```cpp
enum class ValidationType
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | 0 | Tidak ada validasi yang dilakukan, dan tidak ada kesalahan validasi yang dilempar. Pengaturan ini membuat parser non-validasi yang mematuhi XML 1.0. |
| Auto | 1 | Melakukan validasi jika informasi DTD atau skema ditemukan. |
| DTD | 2 | Melakukan validasi menurut DTD. |
| XDR | 3 | Melakukan validasi menurut skema XML-Data Reduced (XDR), termasuk skema XDR inline. Skema XDR dikenali menggunakan awalan ruang nama **x-schema** atau nilai [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/). |
| Schema | 4 | Melakukan validasi menurut skema bahasa definisi XML [Schema](../../system.xml.schema/) (XSD), termasuk XML Schema inline. XML Schema dikaitkan dengan URI ruang nama baik dengan menggunakan atribut **schemaLocation** atau **Schemas** yang disediakan. |

## Lihat Juga

* Ruang nama [System::Xml](../)
* Pustaka [Aspose.Slides](../../)