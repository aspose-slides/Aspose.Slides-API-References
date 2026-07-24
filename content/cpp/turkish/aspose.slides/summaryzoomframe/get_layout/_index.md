---
title: get_Layout()
second_title: Aspose.Slides for C++ API Referansı
description: Çerçevedeki Summary Zoom Bölümlerinin düzenini alır. Varsayılan değer GridLayout'tir.
type: docs
weight: 1
url: /tr/aspose.slides/summaryzoomframe/get_layout/
---
## SummaryZoomFrame::get_Layout() metodu

Çerçevedeki Özet Yakınlaştırma Bölümlerinin düzenini alır. Varsayılan değer GridLayout'tir.

```cpp
ZoomLayout Aspose::Slides::SummaryZoomFrame::get_Layout() override
```

## Açıklamalar

Örnek, indeksle Summary Zoom [Section](../../section/) öğesini almayı gösterir:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Ayrıca Bakınız

* Enum [ZoomLayout](../../zoomlayout/)
* Sınıf [SummaryZoomFrame](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)