---
title: get_ErrorBarsXFormat()
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili ErrorBars dari seri dengan arah X.
type: docs
weight: 222
url: /id/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() metode


Mewakili ErrorBars dari seri dengan arah X.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## Catatan


ErrorBars dengan arah X tersedia untuk seri bertipe area, bar, scatter, dan bubble. Untuk tipe grafik lainnya properti ini mengembalikan null (termasuk grafik 3D). Jika menggunakan nilai khusus, gunakan koleksi DataPoints untuk menentukan nilai (dengan properti [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)). 

Baca-saja [IErrorBarsFormat](../../ierrorbarsformat/). 
## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IErrorBarsFormat](../../ierrorbarsformat/)
* Kelas [ChartSeries](../)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)