---
title: ICaptionsCollection
second_title: Aspose.Slides için Java API Referansı
description: Kapanış altyazılarının bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/icaptionscollection/
---
**Uygulanan Tüm Arabirimler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

Kapanış altyazılarının bir koleksiyonunu temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksdeki kapanış altyazılarını döndürür. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | WebVTT kapanış altyazılarını koleksiyonun sonuna ekler. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | WebVTT kapanış altyazılarını bir akıştan alarak koleksiyonun sonuna ekler. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Belirtilen kapanış altyazılarını koleksiyondan kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksdeki kapanış altyazılarını kaldırır. |
| [clear()](#clear--) | Koleksiyondan tüm kapanış altyazılarını kaldırır. |
| [getCount()](#getCount--) | Koleksiyondaki öğe sayısını döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```

Belirtilen indeksdeki kapanış altyazılarını döndürür. Yalnızca okunabilir [ICaptions](../../com.aspose.slides/icaptions).

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

WebVTT kapanış altyazılarını koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| label | java.lang.String | Kapanış altyazılarının etiketi. |
| filePath | java.lang.String | WebVTT dosyasının yolu. |

**Döndürür:**
[ICaptions](../../com.aspose.slides/icaptions) - Eklenen [ICaptions](../../com.aspose.slides/icaptions) örneği.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```

WebVTT kapanış altyazılarını bir akıştan alarak koleksiyonun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| label | java.lang.String | Kapanış altyazılarının etiketi. |
| stream | java.io.InputStream | WebVTT biçiminde veri içeren giriş akışı. |

**Döndürür:**
[ICaptions](../../com.aspose.slides/icaptions) - Eklenen [ICaptions](../../com.aspose.slides/icaptions) örneği.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```

Koleksiyondan belirtilen kapanış altyazılarını kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Kaldırılacak kapanış altyazıları. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Belirtilen indeksdeki kapanış altyazılarını kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak kapanış altyazılarının indeksi. |

### clear() {#clear--}
```
public abstract void clear()
```

Koleksiyondan tüm kapanış altyazılarını kaldırır.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Koleksiyondaki öğe sayısını döndürür. Yalnızca okunabilir  int .

**Döndürür:**
int