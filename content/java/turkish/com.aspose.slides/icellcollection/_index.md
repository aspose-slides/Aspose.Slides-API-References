---
title: ICellCollection
second_title: Aspose.Slides için Java API Referansı
description: Hücrelerin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/icellcollection/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Hücrelerin bir koleksiyonunu temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen konumdaki bir hücreyi döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

Belirtilen konumdaki bir hücreyi döndürür. Salt okunur [ICell](../../com.aspose.slides/icell).

--------------------

Hücre birleştirilmişse, birden fazla indis için bir CellEx nesnesi döndürülebilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ICell](../../com.aspose.slides/icell)