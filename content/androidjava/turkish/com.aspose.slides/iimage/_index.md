---
title: IImage
second_title: Aspose.Slides for Android için Java API Referansı
description: Raster veya vektör görüntüyü temsil eder.
type: docs
url: /tr/com.aspose.slides/iimage/
---
**Tüm Uygulanan Arayüzler:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Raster veya vektör görüntüyü temsil eder.

--------------------

Bu arabirim, raster ve vektör görüntülerin her ikisinin de işlenmesi için ortak bir soyutlama sağlar. Uygulamalar, temel görüntü türüne bağlı olarak değişebilir.
## Methods

| Method | Description |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Görüntüyü bir dosyaya kaydeder. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Görüntüyü belirtilen formatta bir dosyaya kaydeder. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Görüntüyü belirtilen formatta bir akışa kaydeder. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Görüntüyü belirtilen formatta ve kalitede bir dosyaya kaydeder. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Görüntüyü belirtilen formatta ve kalitede bir akışa kaydeder. |
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

Görüntüyü belirtilen formatta ve kalitede bir dosyaya kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | java.lang.String | Görüntünün kaydedileceği dosyanın yolu. |
| format | int | Görüntü formatı. |
| quality | int | Kaydedilen görüntünün kalitesi (0-100). Bu parametre yalnızca [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) içinde kaydetmeye etki eder; diğer tüm formatlarda yoksayılır. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

Görüntüyü belirtilen formatta ve kalitede bir akışa kaydeder.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.OutputStream | Görüntünün kaydedileceği akış. |
| format | int | Görüntü formatı. |
| quality | int | Kaydedilen görüntünün kalitesi (0-100). Bu parametre yalnızca [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg) içinde kaydetmeye etki eder; diğer tüm formatlarda yoksayılır. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```

Görüntünün boyutunu alır.

**Dönüş:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Görüntünün piksel cinsinden genişliğini alır.

**Dönüş:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Görüntünün piksel cinsinden yüksekliğini alır.

**Dönüş:**
int