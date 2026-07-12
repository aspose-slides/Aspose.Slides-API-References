---
title: IColumnCollection
second_title: Aspose.Slides Android için Java API Referansı
description: Bir tablodaki sütun koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/icolumncollection/
---
**Tüm Uygulanan Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Bir tablodaki sütun koleksiyonunu temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki sütunu döndürür. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Belirtilen şablon satırının bir kopyasını oluşturur ve bir tablonun altına ekler. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Belirtilen şablon sütununun bir kopyasını oluşturur ve bir tabloda belirtilen konuma ekler. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Belirtilen konumdaki bir sütunu bir tablodan kaldırır. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

Belirtilen dizindeki sütunu döndürür. Salt okunur [IColumn](../../com.aspose.slides/icolumn).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IColumn](../../com.aspose.slides/icolumn)

### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Belirtilen şablon satırının bir kopyasını oluşturur ve bir tablonun altına ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Şablon olarak kullanılan sütun. |
| withAttachedColumns | boolean | Şablon satırına bağlı tüm sütunları da kopyalamak için true. |

**Döndürür:**
com.aspose.slides.IColumn[] - Eklenen sütunlar.

### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Belirtilen şablon sütununun bir kopyasını oluşturur ve bir tabloda belirtilen konuma ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Yeni bir sütunun indeksi. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Şablon olarak kullanılan sütun. |
| withAttachedColumns | boolean | Şablon sütununa bağlı tüm sütunları da kopyalamak için true. |

**Döndürür:**
com.aspose.slides.IColumn[] - Eklenen sütunlar.

### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Belirtilen konumdaki bir sütunu bir tablodan kaldırır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstColumnIndex | int | Silinecek sütunun indeksi. |
| withAttachedRows | boolean | Bağlı tüm sütunları da silmek için true. |