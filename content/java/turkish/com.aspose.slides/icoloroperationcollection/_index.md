---
title: IColorOperationCollection
second_title: Aspose.Slides Java API Referansı
description: Renk dönüşüm işlemlerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/icoloroperationcollection/
---
**Tüm Uygulanan Arabirimler:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Renk dönüşüm işlemlerinin bir koleksiyonunu temsil eder.
## Yöntemler

| Method | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki işlemi alır veya ayarlar. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Belirtilen indeksteki işlemi alır veya ayarlar. |
| [add(int operation, float parameter)](#add-int-float-) | Yeni bir işlemi koleksiyonun sonuna ekler. |
| [add(int operation)](#add-int-) | Yeni bir işlemi koleksiyonun sonuna ekler. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Yeni bir işlemi bir koleksiyona ekler. |
| [insert(int position, int operation)](#insert-int-int-) | Yeni bir işlemi bir koleksiyona ekler. |
| [removeAt(int index)](#removeAt-int-) | Renk işlemini bir koleksiyondan kaldırır. |
| [clear()](#clear--) | Tüm renk işlemlerini kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

Belirtilen indeksteki işlemi alır veya ayarlar. Okunur/yazılır [IColorOperation](../../com.aspose.slides/icoloroperation).

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

Belirtilen indeksteki işlemi alır veya ayarlar. Okunur/yazılır [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

Yeni bir işlemi koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| operation | int | İşlem türü. |
| parameter | float | İşlemin parametresi. |

**Döndürür:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Eklenen işlem.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

Yeni bir işlemi koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| operation | int | İşlem türü. |

**Döndürür:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Eklenen işlem.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

Yeni bir işlemi bir koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | int | İşlemin ekleneceği indeks. |
| operation | int | İşlem türü. |
| parameter | float | İşlemin parametresi. |

**Döndürür:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Eklenen işlem.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

Yeni bir işlemi bir koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | int | İşlemin ekleneceği indeks. |
| operation | int | İşlem türü. |

**Döndürür:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Eklenen işlem.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Renk işlemini bir koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak renk işleminin indeksi. |

### clear() {#clear--}
```
public abstract void clear()
```

Tüm renk işlemlerini kaldırır.