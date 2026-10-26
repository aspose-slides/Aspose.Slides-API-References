---
title: IColumnCollection
second_title: Aspose.Slides for Java API Referansı
description: Bir tabloda sütunların koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/icolumncollection/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Bir tabloda sütunların koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki sütunu döndürür. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Belirtilen şablon satırının bir kopyasını oluşturur ve tablonun altına ekler. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Belirtilen şablon sütununun bir kopyasını oluşturur ve tablonun belirtilen konumuna ekler. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Bir tablodan belirtilen konumdaki bir sütunu kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

Belirtilen indeksteki sütunu döndürür. Salt okunur [IColumn](../../com.aspose.slides/icolumn).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Belirtilen şablon satırının bir kopyasını oluşturur ve tablonun altına ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Şablon olarak kullanılan sütun. |
| withAttachedColumns | boolean | Şablon satırına bağlı tüm sütunları da kopyalamak için True. |

**Döndürür:**
com.aspose.slides.IColumn[] - Eklenen sütunlar.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Belirtilen şablon sütununun bir kopyasını oluşturur ve tablonun belirtilen konumuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni bir sütunun indeksi. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Şablon olarak kullanılan sütun. |
| withAttachedColumns | boolean | Şablon sütununa bağlı tüm sütunları da kopyalamak için True. |

**Döndürür:**
com.aspose.slides.IColumn[] - Eklenen sütunlar.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Bir tablodan belirtilen konumdaki bir sütunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstColumnIndex | int | Silinecek bir sütunun indeksi. |
| withAttachedRows | boolean | Bağlı tüm sütunları da silmek için True. |