---
title: CaptionsCollection
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Kapalı altyazıların bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/captionscollection/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

Kapalı altyazıların bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki kapalı altyazıyı döndürür. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | WebVTT kapalı altyazılarını koleksiyonun sonuna ekler. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | WebVTT kapalı altyazılarını akıştan koleksiyonun sonuna ekler. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Belirtilen kapalı altyazıyı koleksiyondan kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen dizindeki kapalı altyazıyı kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm kapalı altyazıları kaldırır. |
| [getCount()](#getCount--) | Koleksiyondaki öğelerin sayısını döndürür. |
| [iterator()](#iterator--) | Koleksiyon üzerinde gezinmek için bir yineleyici döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```


Belirtilen dizindeki kapalı altyazıyı döndürür. Salt okunur [ICaptions](../../com.aspose.slides/icaptions).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş Değeri:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```


WebVTT kapalı altyazılarını koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| label | java.lang.String | Kapalı altyazının etiketi. |
| filePath | java.lang.String | WebVTT dosyasının yolu. |

**Dönüş Değeri:**
[ICaptions](../../com.aspose.slides/icaptions) - Eklenen [ICaptions](../../com.aspose.slides/icaptions) örneği.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```


WebVTT kapalı altyazılarını akıştan koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| label | java.lang.String | Kapalı altyazının etiketi. |
| stream | java.io.InputStream | WebVTT biçiminde veri içeren giriş akışı. |

**Dönüş Değeri:**
[ICaptions](../../com.aspose.slides/icaptions) - Eklenen [ICaptions](../../com.aspose.slides/icaptions) örneği.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```


Belirtilen kapalı altyazıyı koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Kaldırılacak kapalı altyazı. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Belirtilen dizindeki kapalı altyazıyı kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak kapalı altyazının dizini. |

### clear() {#clear--}
```
public final void clear()
```


Koleksiyondaki tüm kapalı altyazıları kaldırır.

### getCount() {#getCount--}
```
public final int getCount()
```


Koleksiyondaki öğelerin sayısını döndürür. Salt okunur int .

**Dönüş Değeri:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```


Koleksiyon üzerinde gezinmek için bir yineleyici döndürür.

**Dönüş Değeri:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - Koleksiyon üzerinde gezinmek için kullanılabilecek bir System.Collections.Generic.IEnumerator1.