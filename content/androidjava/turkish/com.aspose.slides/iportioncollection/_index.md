---
title: IPortionCollection
second_title: Aspose.Slides Android için Java API Referansı
description: Portion'ların bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/iportioncollection/
---
**Uygulanan Tüm Arabirimler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Portion'ların bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [getCount()](#getCount--) | Koleksiyonda gerçekte bulunan öğelerin sayısını alır. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Koleksiyonun sonuna bir Portion ekler. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Koleksiyonda belirli bir portion'ın indeksini belirler. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Belirtilen indekste bir Portion ekler. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir değerin bulunup bulunmadığını belirler. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir nesnenin ilk oluşumunu kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyonda belirtilen indeksteki öğeyi kaldırır. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

Belirtilen indeksteki öğeyi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş:**
[IPortion](../../com.aspose.slides/iportion)

### getCount() {#getCount--}
```
public abstract int getCount()
```

Koleksiyonda gerçekte bulunan öğelerin sayısını alır. Salt okunur int.

**Dönüş:**
int

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

Koleksiyonun sonuna bir Portion ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Koleksiyonun sonuna eklenecek Portion. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

Koleksiyonda belirli bir portion'ın indeksini belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Koleksiyonda bulunacak parça. |

**Dönüş:**
int - Koleksiyonda bulunursa öğenin indeksi; aksi takdirde -1.

### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

Belirtilen indekste bir Portion ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Portion'ın ekleneceği sıfır tabanlı indeks. |
| value | [IPortion](../../com.aspose.slides/iportion) | Eklemek için Portion. |

### clear() {#clear--}
```
public abstract void clear()
```

Koleksiyondaki tüm öğeleri kaldırır.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir değerin bulunup bulunmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunacak nesne. |

**Dönüş:**
boolean - item [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunursa doğru; aksi takdirde yanlış.

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir nesnenin ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde kaldırılacak nesne. |

**Dönüş:**
boolean - item [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde başarıyla kaldırıldıysa doğru; aksi takdirde yanlış. Bu yöntem ayrıca öğe orijinal [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunamazsa da yanlış döndürür.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Koleksiyonda belirtilen indeksteki öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |