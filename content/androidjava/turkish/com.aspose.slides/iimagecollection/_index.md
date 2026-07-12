---
title: IImageCollection
second_title: Aspose.Slides for Android için Java API Referansı
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
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Görüntüyü indeksine göre döndürür. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Sunuma bir görüntü ekler. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Akıştan bir görüntüyü sunuma ekler. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Akıştan bir görüntü oluşturur ve sunuma ekler. |
| [addImage(byte[] buffer)](#addImage-byte---) | Belirtilen tampondan bir görüntüyü sunuma ekler. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Başka bir sunumdan bir görüntünün kopyasını ekler. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | SVG nesnesinden bir görüntüyü sunuma ekler. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```

Görüntüyü indeksine göre döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | İndeks. |

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Görüntü.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```

Sunuma bir görüntü ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Eklemek için görüntü. |

--------------------
Bu metod, WMF/EMF metafilelerini sunuma eklemeden önce raster PNG görüntüsüne dönüştürür. |

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen görüntü.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

Akıştan bir görüntüyü sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Görüntüyü eklemek için akış. |

--------------------
Bu metod, WMF/EMF metafilelerini raster PNG görüntüsüne dönüştürmeden sunuma ekleyebilir. |

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen görüntü.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Akıştan bir görüntü oluşturur ve sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Görüntü dosyasını eklemek için akış. |
| loadingStreamBehavior | int | Akışa uygulanacak davranış. |

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

Belirtilen tampondan bir görüntüyü sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | byte[] | Tampon. |

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen görüntü.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

Başka bir sunumdan bir görüntünün kopyasını ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Kaynak görüntü. |

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen görüntü.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

SVG nesnesinden bir görüntüyü sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG görüntü nesnesi [ISvgImage](../../com.aspose.slides/isvgimage) |

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen görüntü.