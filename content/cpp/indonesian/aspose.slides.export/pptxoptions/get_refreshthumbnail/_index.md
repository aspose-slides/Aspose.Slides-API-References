---
title: get_RefreshThumbnail()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah thumbnail presentasi akan disegarkan. Baca bool. Nilai default adalah true.
type: docs
weight: 53
url: /id/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() metode

Menentukan apakah thumbnail presentasi akan disegarkan. Baca **bool**. Nilai default adalah **true**.

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## Catatan

Ketika nilai opsi **true**, thumbnail baru akan dihasilkan.

Ketika nilai opsi **false**, thumbnail saat ini akan disimpan apa adanya.

Contoh:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Lihat Juga

* Kelas [PptxOptions](../)
* Ruang Nama [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)