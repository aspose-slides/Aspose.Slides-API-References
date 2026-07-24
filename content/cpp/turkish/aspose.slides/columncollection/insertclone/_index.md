---
title: InsertClone()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen şablon sütununun bir kopyasını oluşturur ve tablo içinde belirtilen konuma ekler.
type: docs
weight: 66
url: /tr/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) metodu


Belirtilen şablon sütununun bir kopyasını oluşturur ve tablo içinde belirtilen konuma ekler.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Yeni bir sütunun indeksi. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) şablon olarak kullanılan. |
| withAttachedColumns | **bool** | Şablon sütununa bağlı tüm sütunları da kopyalamak için True. |

### Dönüş Değeri

Eklenen sütunlar.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IColumn](../../icolumn/)
* Sınıf [ColumnCollection](../)
* İsim Uzayı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)