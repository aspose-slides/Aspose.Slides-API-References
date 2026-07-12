---
title: IGradientStopCollection
second_title: Android için Aspose.Slides Java API Referansı
description: Gradient duraklarının bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/igradientstopcollection/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Gradient duraklarının bir koleksiyonunu temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | İndeksle gradient durakını döndürür. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Yeni gradient durak oluşturur ve koleksiyonun sonuna ekler. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Yeni gradient durak oluşturur ve koleksiyonun sonuna ekler. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Yeni gradient durak oluşturur ve koleksiyonun sonuna ekler. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Yeni gradient durak oluşturur ve koleksiyonda belirtilen indekse ekler. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Yeni gradient durak oluşturur ve koleksiyonda belirtilen indekse ekler. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Yeni gradient durak oluşturur ve koleksiyonda belirtilen indekse ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki gradient durakını kaldırır. |
| [clear()](#clear--) | Bir koleksiyondan tüm gradient duraklarını kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```


İndeksle gradient durakını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```


Yeni gradient durak oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | float | Yeni gradient durakının konumu. |
| color | java.lang.Integer | Yeni gradient durakının rengi. |

**Döndürür:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Koleksiyondaki yeni gradient durakının indeksi.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```


Yeni gradient durak oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | float | Yeni gradient durakının konumu. |
| presetColor | int | Yeni gradient durakının rengi. |

**Döndürür:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Koleksiyondaki yeni gradient durakının indeksi.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```


Yeni gradient durak oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | float | Yeni gradient durakının konumu. |
| schemeColor | int | Yeni gradient durakının rengi. |

**Döndürür:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Koleksiyondaki yeni gradient durakının indeksi.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```


Yeni gradient durak oluşturur ve koleksiyonda belirtilen indeks'e ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni gradient durakının ekleneceği koleksiyondaki indeks. |
| position | float | Yeni gradient durakının konumu. |
| color | java.lang.Integer | Yeni gradient durakının rengi. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```


Yeni gradient durak oluşturur ve koleksiyonda belirtilen indeks'e ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni gradient durakının ekleneceği koleksiyondaki indeks. |
| position | float | Yeni gradient durakının konumu. |
| presetColor | int | Yeni gradient durakının rengi. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```


Yeni gradient durak oluşturur ve koleksiyonda belirtilen indeks'e ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni gradient durakının ekleneceği koleksiyondaki indeks. |
| position | float | Yeni gradient durakının konumu. |
| schemeColor | int | Yeni gradient durakının rengi. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Belirtilen indeksteki gradient durakını kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken gradient durakının indeksi. |

### clear() {#clear--}
```
public abstract void clear()
```


Bir koleksiyondan tüm gradient duraklarını kaldırır.