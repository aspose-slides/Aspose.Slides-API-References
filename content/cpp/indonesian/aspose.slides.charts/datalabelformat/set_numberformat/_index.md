---
title: set_NumberFormat()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili string format untuk objek DataLabels. Tulis System::String."
type: docs
weight: 40
url: /id/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat(System::String) metode


Mewakili string format untuk objek DataLabels. Tulis [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## Catatan



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





Jika induk dari objek [DataLabelFormat](../) ini adalah koleksi [DataLabelCollection](../../datalabelcollection/) label data, maka properti ini mendapatkan atau mengatur nilai default dari properti NumberFormat untuk label data baru dalam koleksi [DataLabelCollection](../../datalabelcollection/). Ketika properti ini diatur dengan sebuah nilai, nilai tersebut juga diatur untuk properti NumberFormat untuk semua label data dalam koleksi [DataLabelCollection](../../datalabelcollection/) (i.e. \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" menyebabkan semua DataLabels[i].NumberFormat menjadi val). 



## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [DataLabelFormat](../)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)