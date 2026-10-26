---
title: IRowCollection
second_title: Aspose.Slides for Java API Referansı
description: Tablo satır koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/irowcollection/
---
**Uygulanan Tüm Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Tablo satır koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki öğeyi alır. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Belirtilen şablon satırının bir kopyasını oluşturur ve bir tablonun altına ekler. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Belirtilen şablon satırının bir kopyasını oluşturur ve bir tablonun belirtilen konumuna ekler. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Bir tablodan belirtilen konumdaki satırı kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```


Belirtilen dizindeki öğeyi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş Değeri:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Belirtilen şablon satırının bir kopyasını oluşturur ve bir tablonun altına ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Şablon olarak kullanılan satır. |
| withAttachedRows | boolean | Şablon satırına ekli tüm satırları da kopyalamak için doğru. |

**Dönüş Değeri:**
com.aspose.slides.IRow[] - Eklenen satırlar.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Belirtilen şablon satırının bir kopyasını oluşturur ve bir tablonun belirtilen konumuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni bir satırın indeksi. |
| templ | [IRow](../../com.aspose.slides/irow) | Şablon olarak kullanılan satır. |
| withAttachedRows | boolean | Şablon satırına ekli tüm satırları da kopyalamak için doğru. |

**Dönüş Değeri:**
com.aspose.slides.IRow[] - Eklenen satırlar.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Bir tablodan belirtilen konumdaki satırı kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstRowIndex | int | Silinecek bir satırın indeksi. |
| withAttachedRows | boolean | Şablon satırına ekli tüm satırları da silmek için doğru. |