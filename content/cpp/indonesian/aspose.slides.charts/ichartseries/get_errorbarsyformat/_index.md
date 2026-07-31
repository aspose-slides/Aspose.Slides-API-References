---
title: get_ErrorBarsYFormat()
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili ErrorBars seri dengan arah Y.
type: docs
weight: 235
url: /id/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() metode

Mewakili ErrorBars seri dengan derection Y.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## Keterangan

ErrorBars dengan arah Y tersedia untuk seri yang bertipe area, bar, line, scatter, dan bubble. Untuk tipe chart lainnya properti ini mengembalikan null (termasuk chart 3D). Jika menggunakan nilai khusus, gunakan koleksi DataPoints untuk menentukan nilai (dengan properti [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Hanya baca [IErrorBarsFormat](../../ierrorbarsformat/). 
## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IErrorBarsFormat](../../ierrorbarsformat/)
* Kelas [IChartSeries](../)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)