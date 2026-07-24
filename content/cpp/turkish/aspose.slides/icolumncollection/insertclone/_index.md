---
title: InsertClone()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen şablon sütununun bir kopyasını oluşturur ve tablo içinde belirtilen konuma ekler.
type: docs
weight: 27
url: /tr/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) metodu

Belirtilen şablon sütununun bir kopyasını oluşturur ve tablo içinde belirtilen konuma ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Yeni bir sütunun indeksi. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) şablon olarak kullanılan. |
| withAttachedColumns | **bool** | Şablon sütununa ekli tüm sütunları da kopyalamak için True. |

### Dönüş Değeri

Eklenen sütunlar.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColumn](../../icolumn/)
* Class [IColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)