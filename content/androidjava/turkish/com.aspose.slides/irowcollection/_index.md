---
title: IRowCollection
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Tablo satır koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/irowcollection/
---
**Tüm Gerçekleştirilen Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Tablo satır koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen **index** konumundaki öğeyi alır. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Belirtilen şablon satırının bir kopyasını oluşturur ve tabloyun en altına ekler. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Belirtilen şablon satırının bir kopyasını oluşturur ve tablo içinde belirtilen konuma ekler. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Belirtilen konumdaki bir satırı bir tablodan kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```


Belirtilen **index** konumundaki öğeyi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Belirtilen şablon satırının bir kopyasını oluşturur ve tabloyun en altına ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Şablon olarak kullanılan satır. |
| withAttachedRows | boolean | Şablon satıra ekli tüm satırları da kopyalamak için **true**. |

**Döndürür:**
com.aspose.slides.IRow[] - Eklenen satırlar.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Belirtilen şablon satırının bir kopyasını oluşturur ve tablo içinde belirtilen konuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni bir satırın **index**i. |
| templ | [IRow](../../com.aspose.slides/irow) | Şablon olarak kullanılan satır. |
| withAttachedRows | boolean | Şablon satıra ekli tüm satırları da kopyalamak için **true**. |

**Döndürür:**
com.aspose.slides.IRow[] - Eklenen satırlar.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Belirtilen konumdaki bir satırı bir tablodan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstRowIndex | int | Silinecek satırın **index**i. |
| withAttachedRows | boolean | Ekli tüm satırları da silmek için **true**. |