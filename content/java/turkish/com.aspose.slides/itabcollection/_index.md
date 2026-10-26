---
title: ITabCollection
second_title: Aspose.Slides Java API Referansı
description: Sekmelerin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/itabcollection/
---
**Tüm Uygulanan Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Sekmelerin bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki öğeyi alır. |
| [add(double position, int align)](#add-double-int-) | Koleksiyona bir Sekme ekler. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Koleksiyona bir Sekme ekler. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyondaki belirtilen dizindeki öğeyi kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

Belirtilen dizindeki öğeyi alır. Salt okunur [ITab](../../com.aspose.slides/itab).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```

Koleksiyona bir Sekme ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | double | Sekme konumu. |
| align | int | Sekme hizalaması. |

**Döndürür:**
[ITab](../../com.aspose.slides/itab) - Eklenen sekme.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

Koleksiyona bir Sekme ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Koleksiyonun sonuna eklenecek Sekme nesnesi. |

**Döndürür:**
int - Sekmenin eklendiği dizin.
### clear() {#clear--}
```
public abstract void clear()
```

Koleksiyondaki tüm öğeleri kaldırır.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Koleksiyondaki belirtilen dizindeki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı dizini. |