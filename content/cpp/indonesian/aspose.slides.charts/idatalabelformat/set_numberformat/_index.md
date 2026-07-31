---
title: set_NumberFormat()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili string format untuk objek DataLabels. Tulis System::String."
type: docs
weight: 40
url: /id/aspose.slides.charts/idatalabelformat/set_numberformat/
---
## IDataLabelFormat::set_NumberFormat(System::String) metode

Mewakili string format untuk objek DataLabels. Tulis [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_NumberFormat(System::String value)=0
```

## Keterangan

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

Jika induk dari objek [DataLabelFormat](../../datalabelformat/) ini merupakan koleksi [DataLabelCollection](../../datalabelcollection/) dari data label, maka properti ini memperoleh atau mengatur nilai default properti NumberFormat untuk data label baru dalam koleksi [DataLabelCollection](../../datalabelcollection/). Ketika properti ini diatur dengan suatu nilai, nilai tersebut juga diatur untuk properti NumberFormat untuk semua data label dalam koleksi [DataLabelCollection](../../datalabelcollection/) (misalnya "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" menyebabkan semua DataLabels[i].NumberFormat menjadi val).

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [IDataLabelFormat](../)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Pustaka [Aspose.Slides](../../../)