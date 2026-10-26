---
title: pie_split_by property
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## pie_split_by properti
Menentukan bagaimana cara menentukan titik data mana yang berada di pie atau bar kedua pada diagram pie-of-pie atau bar-of-pie.  
Properti ini bukan hanya milik seri ini tetapi juga semua seri dalam grup seri induk – ini adalah proyeksi dari properti grup yang sesuai.  
Oleh karena itu properti ini bersifat read-only.  
Gunakan properti ParentSeriesGroup untuk mengakses grup seri induk.  
Gunakan properti read/write ParentSeriesGroup.PieSplitBy untuk mengubah nilai.  
Read-only [`PieSplitType`](/slides/python-net/id/aspose.slides.charts/piesplittype).

### Catatan

1) Ini adalah proyeksi dari properti ParentSeriesGroup.PieSplitBy.  
            2) Jika nilai properti adalah PieSplitType.Custom maka Anda dapat menentukan informasi split khusus dengan properti ParentSeriesGroup.PieSplitCustomPoints.

### Definisi:
```python
@property
def pie_split_by(self):
    ...
```

### Lihat Juga
* kelas [`IChartSeries`](/slides/python-net/id/aspose.slides.charts/ichartseries)
* enumerasi [`PieSplitType`](/slides/python-net/id/aspose.slides.charts/piesplittype)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)