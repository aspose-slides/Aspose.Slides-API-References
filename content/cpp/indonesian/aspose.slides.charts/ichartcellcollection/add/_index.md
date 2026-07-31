---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Tambahkan sel baru ke koleksi.
type: docs
weight: 53
url: /id/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) metode

Tambahkan sel baru ke koleksi.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Sel baru yang akan ditambahkan. |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) metode

Membuat [IChartDataCell](../../ichartdatacell/) dari nilai yang ditentukan dan menambahkannya ke koleksi.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Nilainya. |

## Keterangan



Metode ini menambahkan lembar kerja dengan nama AUTO_DATA dan menambahkan semua nilai di sana. Jika Anda menggunakan [IChartDataWorkbook](../../ichartdataworkbook/) untuk menambah atau mengedit nilai [Cell](../../../aspose.slides/cell/), pastikan Anda tidak menggunakan lembar kerja ini. Jumlah maksimum nilai yang ditambahkan menggunakan metode ini tidak boleh melebihi 16711680



## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IChartDataCell](../../ichartdatacell/)
* Kelas [IChartCellCollection](../)
* Kelas [Object](../../../system/object/)
* Ruang Nama [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)