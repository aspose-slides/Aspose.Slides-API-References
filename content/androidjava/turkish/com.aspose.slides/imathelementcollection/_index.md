---
title: IMathElementCollection
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Matematiksel öğeler MathElement'in bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/imathelementcollection/
---
**Tüm Uygulanan Arabirimler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

Matematiksel öğelerin (MathElement) bir koleksiyonunu temsil eder.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [getCount()](#getCount--) | Koleksiyonda gerçekte bulunan öğe sayısını alır. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Bir matematik öğesini koleksiyonun sonuna ekler. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Koleksiyonda belirli bir matematik öğesinin indeksini belirler. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Belirtilen indekste koleksiyona bir matematik öğesi ekler. |
| [clear()](#clear--) | Koleksiyondaki tüm öğeleri kaldırır. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Koleksiyonun belirli bir değeri içerip içermediğini belirler. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Koleksiyondan belirli bir nesnenin ilk görünümünü kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Koleksiyondaki belirtilen indeksteki öğeyi kaldırır. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Belirtilen diziye kopyalar. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```


Belirtilen indeksteki öğeyi alır. Salt okunur [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Alınacak öğenin sıfır tabanlı indeksi |

**Dönüş Değeri:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Koleksiyonda gerçekte bulunan öğe sayısını alır. Salt okunur int.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**Dönüş Değeri:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```


Bir matematik öğesini koleksiyonun sonuna ekler.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Koleksiyonun sonuna eklenecek IMathElement |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```


Koleksiyonda belirli bir matematik öğesinin indeksini belirler.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = collection.indexOf(plusElement);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Koleksiyonda bulunacak öğe. |

**Dönüş Değeri:**
int - Öğenin koleksiyonda bulunması durumunda indeksi; aksi takdirde -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```


Belirtilen indekste koleksiyona bir matematik öğesi ekler.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | IMathElement'in eklenmesi gereken sıfır tabanlı indeks. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Eklenecek IMathElement. |

### clear() {#clear--}
```
public abstract void clear()
```


Koleksiyondaki tüm öğeleri kaldırır.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public abstract boolean contains(IMathElement item)
```


Koleksiyonun belirli bir değeri içerip içermediğini belirler.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  bool contains = collection.contains(plusElement);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Koleksiyonda bulunacak nesne. |

**Dönüş Değeri:**
boolean - öğe koleksiyonda bulunuyorsa true; aksi takdirde false.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```


Koleksiyondan belirli bir nesnenin ilk görünümünü kaldırır.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.remove(plusElement);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Koleksiyondan kaldırılacak nesne. |

**Dönüş Değeri:**
boolean - öğe başarılı bir şekilde koleksiyondan kaldırıldıysa true; aksi takdirde false. Bu yöntem ayrıca öğe orijinal koleksiyonda bulunamazsa false döndürür.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Koleksiyondaki belirtilen indeksteki öğeyi kaldırır.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.removeAt(2);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```


Belirtilen diziye kopyalar.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[collection.Count];
>  collection.copyTo(destinationArray, 0);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Kopyalanacak dizi. |
| arrayIndex | int | Kopyalamaya başlanacak dizin. |