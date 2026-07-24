---
title: InsertTable()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen indekste yeni bir tablo oluşturur ve şekil koleksiyonuna ekler.
type: docs
weight: 482
url: /tr/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) metodu

Belirtilen indekste yeni bir tablo oluşturur ve şekil koleksiyonuna ekler.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Tablonun ekleneceği sıfır tabanlı indeks. |
| x | **float** | Tablonun x koordinatı, puan cinsinden. |
| y | **float** | Tablonun y koordinatı, puan cinsinden. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Tablonun sütun genişliklerini temsil eden double türünden bir dizi, puan cinsinden. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Tablonun satır yüksekliklerini temsil eden double türünden bir dizi, puan cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [ITable](../../itable/).

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [ITable](../../itable/)
* Sınıf [ShapeCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)