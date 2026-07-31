---
title: get_RefreshThumbnail()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah thumbnail presentasi akan diperbarui. Baca bool. Nilai default adalah true.
type: docs
weight: 53
url: /id/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() metode

Menentukan apakah thumbnail presentasi akan diperbarui. Baca **bool**. Nilai default adalah **true**.

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
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

* Kelas [IPptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)