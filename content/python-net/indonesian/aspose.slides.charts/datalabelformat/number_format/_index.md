---
title: number_format property
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides.charts/datalabelformat/number_format/
weight: 80
---
## number_format properti
Mewakili string format untuk objek DataLabels.
            Baca/tulis **str**.

### Catatan
Jika induk dari objek DataLabelFormat ini adalah koleksi DataLabelCollection dari label data, maka ini
            properti mengambil atau mengatur nilai default dari properti NumberFormat untuk data baru 
            label dalam koleksi DataLabelCollection.
            Ketika properti ini diatur dengan sebuah nilai, nilai tersebut juga diatur untuk properti NumberFormat untuk semua label data dalam koleksi DataLabelCollection
            (yaitu "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" menyebabkan semua DataLabels[i].NumberFormat menjadi val).

### Definisi:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```

### Lihat Juga
* kelas [`DataLabelFormat`](/slides/python-net/id/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/id/aspose.slides.charts)
* pustaka [`Aspose.Slides`](/slides/python-net)