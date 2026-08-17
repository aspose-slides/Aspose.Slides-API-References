---
title: IGradientStopCollection
second_title: Aspose.Slides için Java API Referansı
description: Gradyan duraklarının bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/igradientstopcollection/
---
**Tüm Uygulanan Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Gradyan duraklarının bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indekste gradyan durakını döndürür. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Yeni gradyan durakını oluşturur ve koleksiyonun sonuna ekler. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Yeni gradyan durakını oluşturur ve koleksiyonun sonuna ekler. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Yeni gradyan durakını oluşturur ve koleksiyonun sonuna ekler. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Yeni gradyan durakını oluşturur ve koleksiyonda belirtilen indekse ekler. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Yeni gradyan durakını oluşturur ve koleksiyonda belirtilen indekse ekler. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Yeni gradyan durakını oluşturur ve koleksiyonda belirtilen indekse ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indekste bir gradyan durakını kaldırır. |
| [clear()](#clear--) | Bir koleksiyondan tüm gradyan duraklarını kaldırır. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

Belirtilen indekste gradyan durakını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş Değeri:**
[IGradientStop](../../com.aspose.slides/igradientstop)

### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```

Yeni gradyan durakını oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | float | Yeni gradyan durakının konumu. |
| color | java.awt.Color | Yeni gradyan durakının rengi. |

**Dönüş Değeri:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Koleksiyondaki yeni gradyan durakının indeksi.

### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

Yeni gradyan durakını oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | float | Yeni gradyan durakının konumu. |
| presetColor | int | Yeni gradyan durakının rengi. |

**Dönüş Değeri:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Koleksiyondaki yeni gradyan durakının indeksi.

### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

Yeni gradyan durakını oluşturur ve koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| position | float | Yeni gradyan durakının konumu. |
| schemeColor | int | Yeni gradyan durakının rengi. |

**Dönüş Değeri:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Koleksiyondaki yeni gradyan durakının indeksi.

### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```

Yeni gradyan durakını oluşturur ve koleksiyonda belirtilen indekse ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni gradyan durakının ekleneceği koleksiyondaki indeks. |
| position | float | Yeni gradyan durakının konumu. |
| color | java.awt.Color | Yeni gradyan durakının rengi. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

Yeni gradyan durakını oluşturur ve koleksiyonda belirtilen indekse ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni gradyan durakının ekleneceği koleksiyondaki indeks. |
| position | float | Yeni gradyan durakının konumu. |
| presetColor | int | Yeni gradyan durakının rengi. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

Yeni gradyan durakını oluşturur ve koleksiyonda belirtilen indekse ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni gradyan durakının ekleneceği koleksiyondaki indeks. |
| position | float | Yeni gradyan durakının konumu. |
| schemeColor | int | Yeni gradyan durakının rengi. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Belirtilen indekste bir gradyan durakını kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken gradyan durakının indeksi. |

### clear() {#clear--}
```
public abstract void clear()
```

Bir koleksiyondan tüm gradyan duraklarını kaldırır.