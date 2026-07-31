---
title: set_RefreshThumbnail()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah thumbnail presentasi akan disegarkan. Tulis bool. Nilai default adalah true.
type: docs
weight: 66
url: /id/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) metode

Menentukan apakah thumbnail presentasi akan disegarkan. Tulis **bool**. Nilai default adalah **true**.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
```

## Keterangan

Ketika nilai opsi adalah **true**, thumbnail baru akan dihasilkan.

Ketika nilai opsi adalah **false**, thumbnail saat ini akan disimpan apa adanya.

Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Lihat Juga

* Kelas [IPptxOptions](../)
* Ruang nama [Aspose::Slides::Export](../../)
* Perpustakaan [Aspose.Slides](../../../)