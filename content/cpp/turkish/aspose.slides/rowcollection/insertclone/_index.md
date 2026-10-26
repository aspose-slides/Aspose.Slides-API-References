---
title: InsertClone()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen şablon satırının bir kopyasını oluşturur ve tablo içinde belirtilen konuma ekler.
type: docs
weight: 66
url: /tr/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) metodu

Belirtilen şablon satırının bir kopyasını oluşturur ve tablo içinde belirtilen konuma ekler.

```cpp
System::ArrayPtr<System::SharedPtr<IRrow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Yeni bir satırın indeksi. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) şablon olarak kullanılan. |
| withAttachedRows | **bool** | Şablon satırına ekli tüm satırları da kopyalamak için True. |

### Dönüş Değeri

Eklenen satırlar.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IRow](../../irow/)
* Sınıf [RowCollection](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)