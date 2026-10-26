---
title: AddClone()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen şablon satırının bir kopyasını oluşturur ve tablonun altına ekler.
type: docs
weight: 14
url: /tr/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) method

Belirtilen şablon satırının bir kopyasını oluşturur ve tablonun altına ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) şablon olarak kullanılan. |
| withAttachedColumns | **bool** | Şablon satırına bağlı tüm sütunları da kopyalamak için True. |

### Dönüş Değeri

Eklenen sütunlar.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IColumn](../../icolumn/)
* Sınıf [IColumnCollection](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)