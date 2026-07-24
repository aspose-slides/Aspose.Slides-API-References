---
title: AddClone()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen şablon satırının bir kopyasını oluşturur ve tablonun altına ekler.
type: docs
weight: 53
url: /tr/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) metodu

Belirtilen şablon satırının bir kopyasını oluşturur ve tabloyun altına ekler.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | Şablon olarak kullanılan [Column](../../column/). |
| withAttachedColumns | **bool** | Şablon satırına bağlı tüm sütunların da kopyalanması için True. |

### Dönüş Değeri

Eklenen sütunlar.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColumn](../../icolumn/)
* Class [ColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)