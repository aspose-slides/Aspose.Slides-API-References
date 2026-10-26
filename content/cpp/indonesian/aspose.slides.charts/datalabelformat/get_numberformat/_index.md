---
title: get_NumberFormat()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili string format untuk objek DataLabels. Baca System::String."
type: docs
weight: 27
url: /id/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() metode


Mewakili string format untuk objek DataLabels. Baca [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## Keterangan



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





Jika induk dari objek [DataLabelFormat](../) ini adalah kumpulan [DataLabelCollection](../../datalabelcollection/) label data, maka properti ini mendapatkan atau mengatur nilai default properti NumberFormat untuk label data baru dalam kumpulan [DataLabelCollection](../../datalabelcollection/). Ketika properti ini diatur dengan sebuah nilai, nilai tersebut juga diatur untuk properti NumberFormat untuk semua label data dalam kumpulan [DataLabelCollection](../../datalabelcollection/) (misalnya "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" menyebabkan semua DataLabels[i].NumberFormat menjadi val). 



## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [DataLabelFormat](../)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Perpustakaan [Aspose.Slides](../../../)