---
title: IImageCollection
second_title: Aspose.Slides for Java API Referansı
description: PPImage koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/iimagecollection/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

PPImage koleksiyonunu temsil eder.
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | İndeksine göre image döndürür. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Bir sunuma image ekler. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Bir akıştan bir sunuma image ekler. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Bir akıştan bir sunuma image oluşturur ve ekler. |
| [addImage(byte[] buffer)](#addImage-byte---) | Belirtilen tampondan bir sunuma image ekler. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Başka bir sunumdan image'ın bir kopyasını ekler. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | SVG nesnesinden bir sunuma image ekler. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```


İndeksine göre image döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | İndeks. |

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Image.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```


Bir sunuma image ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Eklenecek image. |

--------------------

Bu yöntem, bir sunuma eklemeden önce WMF/EMF metafile'lerini raster PNG görüntüsüne dönüştürür.

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen image.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```


Bir akıştan bir sunuma image ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | image eklemek için akış. |

--------------------

Bu yöntem, WMF/EMF metafile'lerini raster PNG görüntüsüne dönüştürmeden bir sunuma ekleyebilir.

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen image.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Bir akıştan bir sunuma image oluşturur ve ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | image dosyasını eklemek için akış. |
| loadingStreamBehavior | int | Akışa uygulanacak davranış. |

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```


Belirtilen tampondan bir sunuma image ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | byte[] | Tampon. |

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen image.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```


Başka bir sunumdan image'ın bir kopyasını ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Kaynak image. |

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen image.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```


SVG nesnesinden bir sunuma image ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG görüntü nesnesi [ISvgImage](../../com.aspose.slides/isvgimage) |

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen image.