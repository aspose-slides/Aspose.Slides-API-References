---
title: ITabCollection
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Sekmelerin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/itabcollection/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Sekmelerin bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [add(double position, int align)](#add-double-int-) | Bir Tab'ı koleksiyona ekler. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Bir Tab'ı koleksiyona ekler. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyondaki belirtilen indeksteki öğeyi kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```


Belirtilen indeksteki öğeyi alır. Salt okunur [ITab](../../com.aspose.slides/itab).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```


Bir Tab'ı koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | double | Tab konumu. |
| align | int | Tab hizalaması. |

**Dönüş:**
[ITab](../../com.aspose.slides/itab) - Eklenecek Tab.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```


Bir Tab'ı koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Koleksiyonun sonuna eklenecek Tab nesnesi. |

**Dönüş:**
int - Sekmenin eklendiği indeks.
### clear() {#clear--}
```
public abstract void clear()
```


Koleksiyondaki tüm öğeleri kaldırır.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Koleksiyondaki belirtilen indeksteki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |