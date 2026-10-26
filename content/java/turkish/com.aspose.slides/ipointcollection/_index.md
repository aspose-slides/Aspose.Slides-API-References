---
title: IPointCollection
second_title: Aspose.Slides for Java API Referansı
description: Bölümlerin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ipointcollection/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPointCollection extends System.Collections.Generic.IGenericEnumerable<IPoint>
```

Bölümler koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Koleksiyondaki nokta sayısını döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki bir noktayı döndürür. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Koleksiyondaki nokta sayısını döndürür. Salt okunur int.

**Döndürür:**  
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IPoint get_Item(int index)
```

Belirtilen indeksteki bir noktayı döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Öğenin indeksi. |

**Döndürür:**
[IPoint](../../com.aspose.slides/ipoint) - [IPoint](../../com.aspose.slides/ipoint) nesnesi.