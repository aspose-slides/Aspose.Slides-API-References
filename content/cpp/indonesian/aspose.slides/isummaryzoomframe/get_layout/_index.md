---
title: get_Layout()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan tata letak Bagian Summary Zoom dalam frame. Nilai default adalah GridLayout.
type: docs
weight: 1
url: /id/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() metode

Mendapatkan tata letak Bagian Summary Zoom dalam frame. Nilai default adalah GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## Catatan

Contoh ini menunjukkan cara mendapatkan elemen [Section](../../section/) Summary Zoom berdasarkan indeks:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Lihat Juga

* Enum [ZoomLayout](../../zoomlayout/)
* Kelas [ISummaryZoomFrame](../)
* Ruang nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)