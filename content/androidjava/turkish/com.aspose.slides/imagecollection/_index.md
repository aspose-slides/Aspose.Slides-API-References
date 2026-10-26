---
title: ImageCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: PPImage koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/imagecollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

PPImage koleksiyonunu temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyondaki görüntü sayısını döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Başka bir sunumdan bir görüntünün kopyasını ekler. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Bir görüntüyü sunuma ekler. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Bir akıştan sunuma bir görüntü ekler. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Bir akıştan bir görüntü oluşturur ve sunuma ekler. |
| [addImage(byte[] buffer)](#addImage-byte---) | Belirtilen tampondan bir görüntüyü sunuma ekler. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Svg nesnesinden bir görüntüyü sunuma ekler. |
| [iterator()](#iterator--) | Koleksiyonu yineleyen bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
### size() {#size--}
```
public final int size()
```

Koleksiyondaki görüntü sayısını döndürür. Yalnızca okunur  int .

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```

Belirtilen indeksteki öğeyi alır. Yalnızca okunur [IPPImage](../../com.aspose.slides/ippimage).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```

Başka bir sunumdan bir görüntünün kopyasını ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Kaynak görüntü. |

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen görüntü.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```

Bir görüntüyü sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Eklenecek görüntü.

--------------------

Bu yöntem, WMF/EMF metafilelerini sunuma eklemeden önce raster PNG görüntüsüne dönüştürür.

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen görüntü.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```

Bir akıştan sunuma bir görüntü ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Görüntünün ekleneceği akış.

--------------------

Bu yöntem, WMF/EMF metafilelerini raster PNG görüntüsüne dönüştürmeden sunuma ekleyebilir.

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen görüntü.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Bir akıştan bir görüntü oluşturur ve sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Görüntü dosyasının ekleneceği akış. |
| loadingStreamBehavior | int | Akışa uygulanacak davranış. |

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```

Belirtilen tampondan bir görüntüyü sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | byte[] | Tampon. |

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen görüntü.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```

Svg nesnesinden bir görüntüyü sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Svg görüntü nesnesi [ISvgImage](../../com.aspose.slides/isvgimage) |

**Döndürür:**
[IPPImage](../../com.aspose.slides/ippimage) - Eklenen görüntü.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```

Koleksiyonu yineleyen bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
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

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Yalnızca okunur  boolean .

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Yalnızca okunur  Object .

**Döndürür:**
java.lang.Object