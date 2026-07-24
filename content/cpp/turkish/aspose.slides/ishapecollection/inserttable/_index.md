---
title: InsertTable()
second_title: Aspose.Slides C++ API Referansı
description: Yeni bir tablo oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.
type: docs
weight: 443
url: /tr/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method


Yeni bir tablo oluşturur ve belirli indekste şekil koleksiyonuna ekler.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Tabloyu ekleyeceğiniz sıfır-bazlı indeks. |
| x | **float** | Tabloyun x koordinatı, nokta biriminde. |
| y | **float** | Tabloyun y koordinatı, nokta biriminde. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Tablonun sütun genişliklerini temsil eden double değerleri içeren dizi, nokta biriminde. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Tablonun satır yüksekliklerini temsil eden double değerleri içeren dizi, nokta biriminde. |

### Dönüş Değeri

Yeni oluşturulan [ITable](../../itable/).

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [ITable](../../itable/)
* Sınıf [IShapeCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)