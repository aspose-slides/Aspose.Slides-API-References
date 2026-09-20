---
title: show_series_name property
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name properti
Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. 
            True untuk menampilkan nama seri. False untuk menyembunyikannya.
            Baca/tulis **bool**.

### Catatan

Jika parent dari objek DataLabelFormat ini adalah koleksi DataLabelCollection label data maka properti ini mendapatkan atau mengatur nilai default dari properti ShowSeriesName untuk label data baru dalam koleksi DataLabelCollection.
            Mengatur properti ini dengan nilai juga mengatur nilai ini ke properti ShowSeriesName untuk semua label data dalam koleksi DataLabelCollection
            (misalnya "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" menyebabkan semua DataLabels[i].ShowSeriesName menjadi sama dengan val).

### Definisi:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```

### Lihat Juga
* kelas [`IDataLabelFormat`](/slides/python-net/id/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)