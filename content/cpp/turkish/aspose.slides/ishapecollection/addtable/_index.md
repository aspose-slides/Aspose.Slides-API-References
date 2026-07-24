---
title: AddTable()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir tablo oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 430
url: /tr/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) metodu

Yeni bir tablo oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Tablonun x koordinatı, nokta cinsinden. |
| y | **float** | Tablonun y koordinatı, nokta cinsinden. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Tablonun sütunlarının genişliğini temsil eden double dizisi, nokta cinsinden. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Tablonun satırlarının yüksekliğini temsil eden double dizisi, nokta cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [ITable](../../itable/).

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ITable](../../itable/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)