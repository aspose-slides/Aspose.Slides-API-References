---
title: get_HeaderFooterManager()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan manajer HeaderFooter aktual. Hanya baca IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /id/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() metode

Mengembalikan manajer HeaderFooter aktual. Hanya baca [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## Catatan

Contoh berikut menunjukkan cara mengatur visibilitas footer di dalam [Slide](../../slide/) PowerPoint [Presentation](../).
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// Properti IsFooterVisible digunakan untuk menunjukkan bahwa placeholder footer slide tidak ada.
if (!headerFooterManager->get_IsFooterVisible())
{
    // Metode SetFooterVisibility digunakan untuk membuat placeholder footer slide terlihat.
    headerFooterManager->SetFooterVisibility(true);
}

// Properti IsSlideNumberVisible digunakan untuk menunjukkan bahwa placeholder nomor halaman slide tidak ada.
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // Metode SetSlideNumberVisibility digunakan untuk membuat placeholder nomor halaman slide terlihat.
    headerFooterManager->SetSlideNumberVisibility(true);
}

// Properti IsDateTimeVisible digunakan untuk menunjukkan bahwa placeholder tanggal-waktu slide tidak ada.
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // Metode SetFooterVisibility digunakan untuk membuat placeholder tanggal-waktu slide terlihat.
    headerFooterManager->SetDateTimeVisibility(true);
}

// Metode SetFooterText digunakan untuk mengatur teks pada placeholder footer slide.
headerFooterManager->SetFooterText(u"Footer text");
// Metode SetDateTimeText digunakan untuk mengatur teks pada placeholder tanggal-waktu slide.
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
Contoh berikut menunjukkan cara mengatur visibilitas footer anak di dalam [Slide](../../slide/).
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// Method SetFooterAndChildFootersVisibility is used for making a master slide and all child footer placeholders visible.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// Method SetSlideNumberAndChildSlideNumbersVisibility is used for making a master slide and all child page number placeholders visible.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// Method SetDateTimeAndChildDateTimesVisibility is used for making a master slide and all child date-time placeholders visible.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// Method SetFooterAndChildFootersText is used for setting text to master slide and all child footer placeholders.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// Method SetDateTimeAndChildDateTimesText is used for setting text to master slide and all child date-time placeholders.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)