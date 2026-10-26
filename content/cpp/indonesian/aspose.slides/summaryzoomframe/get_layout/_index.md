---
title: get_Layout()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan tata letak Summary Zoom Sections dalam frame. Nilai default adalah GridLayout.
type: docs
weight: 1
url: /id/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() metode

Mendapatkan tata letak Summary Zoom Sections dalam frame. Nilai default adalah GridLayout.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## Catatan

Contoh ini menunjukkan cara mendapatkan elemen Summary Zoom [Section](../../section/) berdasarkan indeks:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Lihat Juga

* Enum [ZoomLayout](../../zoomlayout/)
* Kelas [SummaryZoomFrame](../)
* Namespace [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)