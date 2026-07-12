---
title: IColorOperationCollection
second_title: Aspose.Slides for Android aracılığıyla Java API Referansı
description: Renk dönüşüm işlemlerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/icoloroperationcollection/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Renk dönüşüm işlemlerinin bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki işlemi alır veya ayarlar. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Belirtilen dizindeki işlemi alır veya ayarlar. |
| [add(int operation, float parameter)](#add-int-float-) | Koleksiyonun sonuna yeni bir işlem ekler. |
| [add(int operation)](#add-int-) | Koleksiyonun sonuna yeni bir işlem ekler. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Yeni işlemi bir koleksiyona ekler. |
| [insert(int position, int operation)](#insert-int-int-) | Yeni işlemi bir koleksiyona ekler. |
| [removeAt(int index)](#removeAt-int-) | Renk işlemini bir koleksiyondan kaldırır. |
| [clear()](#clear--) | Tüm renk işlemlerini kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```


Belirtilen dizindeki işlemi alır veya ayarlar. Okunur/yazılır [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```


Belirtilen dizindeki işlemi alır veya ayarlar. Okunur/yazılır [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```


Koleksiyonun sonuna yeni bir işlem ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| operation | int | İşlem türü. |
| parameter | float | İşlemin parametresi. |

**Döndürür:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Ekleme yapılan işlem.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```


Koleksiyonun sonuna yeni bir işlem ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| operation | int | İşlem türü. |

**Döndürür:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Ekleme yapılan işlem.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```


Yeni işlemi bir koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | int | İşlemin ekleneceği dizin. |
| operation | int | İşlem türü. |
| parameter | float | İşlemin parametresi. |

**Döndürür:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Ekleme yapılan işlem.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```


Yeni işlemi bir koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | int | İşlemin ekleneceği dizin. |
| operation | int | İşlem türü. |

**Döndürür:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Ekleme yapılan işlem.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Renk işlemini bir koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak renk işleminin dizini. |

### clear() {#clear--}
```
public abstract void clear()
```


Tüm renk işlemlerini kaldırır.