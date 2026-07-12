---
title: VideoCollection
second_title: Aspose.Slides for Android için Java API Referansı
description: Video nesnelerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/videocollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Video nesnelerinin bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyondaki video dosyalarının sayısını döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki öğeyi alır. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Başka bir sunumdan bir video dosyasının kopyasını ekler. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Akıştan bir video oluşturur ve sunuma ekler. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Byte dizisinden bir video oluşturur ve sunuma ekler. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Videoları belirtilen dizine, belirtilen dizinden başlayarak kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (çok iş parçacıklı) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [iterator()](#iterator--) | Koleksiyon içinde dönen bir yineleyici döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java yineleyicisi döndürür. |
### size() {#size--}
```
public final int size()
```

Koleksiyondaki video dosyalarının sayısını döndürür. Salt-okunur int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

Belirtilen dizindeki öğeyi alır. Salt-okunur [IVideo](../../com.aspose.slides/ivideo).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```

Başka bir sunumdan bir video dosyasının kopyasını ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Kaynak video. |

**Döndürür:**
[IVideo](../../com.aspose.slides/ivideo) - Eklenen video.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Akıştan bir video oluşturur ve sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Video dosyasının ekleneceği akış. |
| loadingStreamBehavior | int | Akışa uygulanacak davranış. |

**Döndürür:**
[IVideo](../../com.aspose.slides/ivideo) - Eklenen [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

Byte dizisinden bir video oluşturur ve sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| videoData | byte[] | Video baytları. |

**Döndürür:**
[IVideo](../../com.aspose.slides/ivideo) - Eklenen video.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Videoları belirtilen dizine, belirtilen dizinden başlayarak kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Dizi. |
| index | int | Dizin. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (çok iş parçacıklı) olup olmadığını gösteren bir değer döndürür. Salt-okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Salt-okunur Object.

**Döndürür:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

Koleksiyon içinde dönen bir yineleyici döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Koleksiyon içinde yinelemek için kullanılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

Tüm koleksiyon için bir java yineleyicisi döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Tüm koleksiyon için bir java.util.Iterator.