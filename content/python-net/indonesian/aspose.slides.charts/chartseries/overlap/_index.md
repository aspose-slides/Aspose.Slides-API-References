---
title: overlap property
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/chartseries/overlap/
weight: 310
---
## properti overlap
Menentukan seberapa banyak bars dan columns tumpang tindih pada diagram 2-D, sebagai persentase (dari -100% hingga 100%).
Properti ini bukan hanya milik seri ini tetapi semua seri dalam grup seri induk.
Ini merupakan proyeksi dari properti yang sesuai dalam grup seri induk, sehingga properti ini hanya-baca.
Untuk mengubah nilai, gunakan properti **ParentSeriesGroup.Overlap** baca/tulis.
Hanya-baca **int**.

### Catatan

Overlap menentukan tingkat tumpang tindih atau jarak antara bars dan columns sebagai persentase lebar mereka:
            - -100%: Jarak maksimum (bars sepenuhnya terpisah).
            - 0%: Bars ditempatkan bersebelahan tanpa tumpang tindih atau jarak.
            - 100%: Tumpang tindih maksimum (bars sepenuhnya tumpang tindih satu sama lain).
            Ini merupakan proyeksi dari properti **ParentSeriesGroup.Overlap**.

### Definisi:
```python
@property
def overlap(self):
    ...
```

### Lihat Juga
* kelas [`ChartSeries`](/slides/python-net/id/aspose.slides.charts/chartseries)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)