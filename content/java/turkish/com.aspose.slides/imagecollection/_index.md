---
title: ImageCollection
second_title: Aspose.Slides Java API Referansı
description: PPImage koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/imagecollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

PPImage koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyondaki resim sayısını döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksdeki öğeyi alır. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Başka bir sunumdan bir resmin kopyasını ekler. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Bir resmi bir sunuma ekler. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Bir akıştan bir resmi bir sunuma ekler. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Bir akıştan bir resim oluşturur ve bir sunuma ekler. |
| [addImage(byte[] buffer)](#addImage-byte---) | Belirtilen tampondan bir resmi bir sunuma ekler. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Svg nesnesinden bir resmi bir sunuma ekler. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir sayıcı döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java yineleyicisi döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
### size() {#size--}
```
public final int size()
```

Koleksiyondaki resim sayısını döndürür. Yalnızca okuma  int .

**Dönüş Değeri:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```

Belirtilen indeksdeki öğeyi alır. Yalnızca okuma [IPPImage](../../com.aspose.slides/ippimage).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş Değeri:**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```

Başka bir sunumdan bir resmin kopyasını ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Kaynak resim. |

**Dönüş Değeri:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen resim.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```

Bir resmi bir sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Eklenecek resim. |

Bu yöntem, WMF/EMF metafilelerini bir sunuma eklemeden önce raster PNG resmine dönüştürür.

**Dönüş Değeri:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen resim.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```

Bir akıştan bir resmi bir sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Resmin ekleneceği akış. |

Bu yöntem, WMF/EMF metafilelerini raster PNG resmine dönüştürmeden bir sunuma ekleyebilir.

**Dönüş Değeri:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen resim.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Bir akıştan bir resim oluşturur ve bir sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Resim dosyasının ekleneceği akış. |
| loadingStreamBehavior | int | Akışa uygulanacak davranış. |

**Dönüş Değeri:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```

Belirtilen tampondan bir resmi bir sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | byte[] | Tampon. |

**Dönüş Değeri:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen resim.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```

Svg nesnesinden bir resmi bir sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Svg resim nesnesi [ISvgImage](../../com.aspose.slides/isvgimage) |

**Dönüş Değeri:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen resim.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```

Koleksiyon içinde yineleme yapan bir sayıcı döndürür.

**Dönüş Değeri:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```

Tüm koleksiyon için bir java yineleyicisi döndürür.

**Dönüş Değeri:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Yalnızca okuma  boolean .

**Dönüş Değeri:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Yalnızca okuma  Object .

**Dönüş Değeri:**
java.lang.Object