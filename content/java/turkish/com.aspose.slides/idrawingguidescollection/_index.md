---
title: IDrawingGuidesCollection
second_title: Aspose.Slides for Java API Referansı
description: Ayarlanabilir çizim kılavuzlarından oluşan bir koleksiyonu temsil eder.
type: docs
url: /tr/com.aspose.slides/idrawingguidescollection/
---
**Tüm Uygulanan Arayüzler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Ayarlanabilir çizim kılavuzlarından oluşan bir koleksiyonu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Çizim kılavuzunu indeksine göre döndürür. |
| [add(byte orientation, float position)](#add-byte-float-) | Çizim kılavuzunu koleksiyonun sonuna ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksdeki çizim kılavuzunu kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [getCount()](#getCount--) | Koleksiyondaki tüm öğelerin sayısını alır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```


Çizim kılavuzunu indeksine göre döndürür. Salt okunur [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş Değeri:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```


Çizim kılavuzunu koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| orientation | byte | Çizim kılavuzunun yönü. |
| position | float | Çizim kılavuzunun noktalar cinsinden konumu. |

**Dönüş Değeri:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Belirtilen indeksdeki çizim kılavuzunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken çizim kılavuzunun indeksi. |

### clear() {#clear--}
```
public abstract void clear()
```


Koleksiyondaki tüm öğeleri kaldırır.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Koleksiyondaki tüm öğelerin sayısını alır. Salt okunur int.

**Dönüş Değeri:**
int