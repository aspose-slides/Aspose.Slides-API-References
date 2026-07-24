---
title: AddClone()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen şablon satırının bir kopyasını oluşturur ve tablonun altına ekler.
type: docs
weight: 53
url: /tr/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) yöntemi

Belirtilen şablon satırının bir kopyasını oluşturur ve tablonun altına ekler.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) şablon olarak kullanılan. |
| withAttachedRows | **bool** | True şablon satırına eklenmiş tüm satırları da kopyalamak için. |

### Dönüş Değeri

Eklenen satırlar.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IRow](../../irow/)
* Class [RowCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)