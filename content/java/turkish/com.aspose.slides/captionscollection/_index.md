---
title: CaptionsCollection
second_title: Aspose.Slides for Java API Referansı
description: Kapalı altyazıların bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/captionscollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

Kapalı altyazıların bir koleksiyonunu temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki kapalı altyazıları döndürür. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | WebVTT kapalı altyazılarını koleksiyonun sonuna ekler. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | WebVTT kapalı altyazılarını akıştan koleksiyonun sonuna ekler. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Belirtilen kapalı altyazıları koleksiyondan kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen dizindeki kapalı altyazıları kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm kapalı altyazıları kaldırır. |
| [getCount()](#getCount--) | Koleksiyondaki öğe sayısını döndürür. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

Belirtilen dizindeki kapalı altyazıları döndürür. Salt okunur [ICaptions](../../com.aspose.slides/icaptions).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```

WebVTT kapalı altyazılarını koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| label | java.lang.String | Kapalı altyazıların etiketi. |
| filePath | java.lang.String | WebVTT dosyasının yolu. |

**Döndürür:**
[ICaptions](../../com.aspose.slides/icaptions) - Eklenen [ICaptions](../../com.aspose.slides/icaptions) örneği.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

WebVTT kapalı altyazılarını bir akıştan alarak koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| label | java.lang.String | Kapalı altyazıların etiketi. |
| stream | java.io.InputStream | WebVTT formatında veri içeren giriş akışı. |

**Döndürür:**
[ICaptions](../../com.aspose.slides/icaptions) - Eklenen [ICaptions](../../com.aspose.slides/icaptions) örneği.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

Belirtilen kapalı altyazıları koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Kaldırılacak kapalı altyazılar. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Belirtilen dizindeki kapalı altyazıları kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak kapalı altyazıların indeksi. |

### clear() {#clear--}
```
public final void clear()
```

Koleksiyondaki tüm kapalı altyazıları kaldırır.

### getCount() {#getCount--}
```
public final int getCount()
```

Koleksiyondaki öğe sayısını döndürür. Salt okunur  int .

**Döndürür:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - A  System.Collections.Generic.IEnumerator1  that can be used to iterate through the collection.