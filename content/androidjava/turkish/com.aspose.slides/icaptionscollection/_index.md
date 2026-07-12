---
title: ICaptionsCollection
second_title: Aspose.Slides for Android için Java API Referansı
description: Kapalı altyazıların bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/icaptionscollection/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

Kapalı altyazıların bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki kapalı altyazıyı döndürür. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | WebVTT kapalı altyazılarını koleksiyonun sonuna ekler. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | WebVTT kapalı altyazılarını bir akıştan koleksiyonun sonuna ekler. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Belirtilen kapalı altyazıyı koleksiyondan kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki kapalı altyazıyı kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm kapalı altyazıları kaldırır. |
| [getCount()](#getCount--) | Koleksiyondaki öğe sayısını döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```


Belirtilen indeksteki kapalı altyazıyı döndürür. Yalnızca okuma [ICaptions](../../com.aspose.slides/icaptions).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```


WebVTT kapalı altyazılarını koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| label | java.lang.String | Kapalı altyazının etiketi. |
| filePath | java.lang.String | WebVTT dosyasının yolu. |

**Döndürür:**
[ICaptions](../../com.aspose.slides/icaptions) - Eklenen [ICaptions](../../com.aspose.slides/icaptions) örneği.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```


WebVTT kapalı altyazılarını bir akıştan koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| label | java.lang.String | Kapalı altyazının etiketi. |
| stream | java.io.InputStream | WebVTT formatında veri içeren giriş akışı. |

**Döndürür:**
[ICaptions](../../com.aspose.slides/icaptions) - Eklenen [ICaptions](../../com.aspose.slides/icaptions) örneği.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```


Belirtilen kapalı altyazıyı koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Kaldırılacak kapalı altyazı. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Belirtilen indeksteki kapalı altyazıyı kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak kapalı altyazının indeksi. |

### clear() {#clear--}
```
public abstract void clear()
```


Koleksiyondaki tüm kapalı altyazıları kaldırır.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Koleksiyondaki öğe sayısını döndürür. Yalnızca okuma  int .

**Döndürür:**
int