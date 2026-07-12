---
title: ICellCollection
second_title: Java API Referansı ile Android için Aspose.Slides
description: Hücrelerin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/icellcollection/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Hücrelerin bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Bir hücreyi konumuna göre döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```


Bir hücreyi konumuna göre döndürür. Salt Okunur [ICell](../../com.aspose.slides/icell).

--------------------

Bir hücre birleştirilmişse, birden fazla indeks için bir CellEx nesnesi döndürülebilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ICell](../../com.aspose.slides/icell)