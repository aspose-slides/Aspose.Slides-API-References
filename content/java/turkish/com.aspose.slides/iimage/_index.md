---
title: IImage
second_title: Aspose.Slides için Java API Referansı
description: Raster veya vektör bir görüntüyü temsil eder.
type: docs
url: /tr/com.aspose.slides/iimage/
---
**Uygulanan Tüm Arabirimler:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Raster veya vektör görüntüyü temsil eder.

--------------------

Bu arabirim, raster ve vektör görüntülerin her ikisini de işlemek için ortak bir soyutlama sağlar. Uygulamalar, temel görüntü türüne bağlı olarak değişebilir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Görüntüyü bir dosyaya kaydeder. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Görüntüyü belirtilen formatta bir dosyaya kaydeder. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Görüntüyü belirtilen formatta bir akışa kaydeder. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Görüntüyü belirtilen formatta ve kaliteyle bir dosyaya kaydeder. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Görüntüyü belirtilen formatta ve kaliteyle bir akışa kaydeder. |
| [getSize()](#getSize--) | Görüntünün boyutunu alır. |
| [getWidth()](#getWidth--) | Görüntünün piksel cinsinden genişliğini alır. |
| [getHeight()](#getHeight--) | Görüntünün piksel cinsinden yüksekliğini alır. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```


Görüntüyü bir dosyaya kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | java.lang.String | Görüntünün kaydedileceği dosyanın yolu. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```


Görüntüyü belirtilen formatta bir dosyaya kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | java.lang.String | Görüntünün kaydedileceği dosyanın yolu. |
| format | int | Görüntü formatı. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```


Görüntüyü belirtilen formatta bir akışa kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Görüntünün kaydedileceği akış. |
| format | int | Görüntü formatı. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```


Görüntüyü belirtilen formatta ve kaliteyle bir dosyaya kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | java.lang.String | Görüntünün kaydedileceği dosyanın yolu. |
| format | int | Görüntü formatı. |
| quality | int | Kaydedilen görüntünün kalitesi (0 ile 100 arasında). Bu parametre yalnızca [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) içinde kaydetmeyi etkiler; diğer tüm formatlarda göz ardı edilir. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```


Görüntüyü belirtilen formatta ve kaliteyle bir akışa kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Görüntünün kaydedileceği akış. |
| format | int | Görüntü formatı. |
| quality | int | Kaydedilen görüntünün kalitesi (0 ile 100 arasında). Bu parametre yalnızca [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) içinde kaydetmeyi etkiler; diğer tüm formatlarda göz ardı edilir. |

### getSize() {#getSize--}
```
public abstract Dimension getSize()
```


Görüntünün boyutunu alır.

**Döndürür:**
java.awt.Dimension
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Görüntünün piksel cinsinden genişliğini alır.

**Döndürür:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Görüntünün piksel cinsinden yüksekliğini alır.

**Döndürür:**
int