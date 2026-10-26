---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides untuk C++ Referensi API
description: Mewakili ErrorBars dari seri dengan arah Y.
type: docs
weight: 235
url: /id/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() metode

Mewakili ErrorBars dari seri dengan arah Y.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## Catatan

ErrorBars dengan arah Y tersedia untuk seri tipe area, bar, line, scatter, dan bubble. Untuk tipe chart lain properti ini mengembalikan null (termasuk chart 3D). Jika menggunakan nilai khusus gunakan koleksi DataPoints untuk menentukan nilai (dengan [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) property).

Hanya-baca [IErrorBarsFormat](../../ierrorbarsformat/). 
## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IErrorBarsFormat](../../ierrorbarsformat/)
* Kelas [ChartSeries](../)
* Ruang nama [Aspose::Slides::Charts](../../)
* Perpustakaan [Aspose.Slides](../../../)