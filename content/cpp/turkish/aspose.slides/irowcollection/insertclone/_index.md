---
title: InsertClone()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen şablon satırının bir kopyasını oluşturur ve tablo içinde belirtilen konuma ekler.
type: docs
weight: 27
url: /tr/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) method

Belirtilen şablon satırının bir kopyasını oluşturur ve tablo içinde belirtilen konuma ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Yeni bir satırın indeksi. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) şablon olarak kullanılan. |
| withAttachedRows | **bool** | Şablon satırına eklenmiş tüm satırları da kopyalamak için true. |

### Dönüş Değeri

Eklenen satırlar.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IRow](../../irow/)
* Class [IRowCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)