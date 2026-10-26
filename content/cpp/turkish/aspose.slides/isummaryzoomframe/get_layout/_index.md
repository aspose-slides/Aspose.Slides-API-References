---
title: get_Layout()
second_title: Aspose.Slides for C++ API Referansı
description: Çerçevedeki Summary Zoom Bölümlerinin düzenini alır. Varsayılan değer GridLayout.
type: docs
weight: 1
url: /tr/aspose.slides/isummaryzoomframe/get_layout/
---
## ISummaryZoomFrame::get_Layout() yöntemi

Çerçevedeki Summary Zoom Bölümlerinin düzenini alır. Varsayılan değer GridLayout.

```cpp
virtual ZoomLayout Aspose::Slides::ISummaryZoomFrame::get_Layout()=0
```

## Açıklamalar

Örnek, Summary Zoom [Section](../../section/) öğesini indeksle almayı gösterir:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
ZoomLayout layout = zoomFrame->get_Layout();
```

## Ayrıca Bakınız

* Enum [ZoomLayout](../../zoomlayout/)
* Sınıf [ISummaryZoomFrame](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)