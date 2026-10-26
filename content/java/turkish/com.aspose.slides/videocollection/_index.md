---
title: VideoCollection
second_title: Aspose.Slides için Java API Referansı
description: Video nesnelerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/videocollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Video nesnelerinin bir koleksiyonunu temsil eder.
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyondaki video dosyalarının sayısını döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Başka bir sunumdan bir video dosyasının kopyasını ekler. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Akıştan bir video oluşturarak sunuma ekler. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Bayt dizisinden bir video oluşturarak sunuma ekler. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Videoları belirtilen diziye belirtilen indeksten başlayarak kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
### size() {#size--}
```
public final int size()
```

Koleksiyondaki video dosyalarının sayısını döndürür. Yalnızca okuma int.

### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

Belirtilen indeksteki öğeyi alır. Yalnızca okuma [IVideo](../../com.aspose.slides/ivideo).

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

Akıştan bir video oluşturarak sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Video dosyasını eklemek için akış. |
| loadingStreamBehavior | int | Akışa uygulanacak davranış. |

**Döndürür:**
[IVideo](../../com.aspose.slides/ivideo) - Eklenen [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

Bayt dizisinden bir video oluşturarak sunuma ekler.

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

Videoları belirtilen diziye belirtilen indeksten başlayarak kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Dizi. |
| index | int | İndeks. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Yalnızca okuma boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Yalnızca okuma Object.

**Döndürür:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Koleksiyon içinde yineleme için kullanılabilecek bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Tüm koleksiyon için bir java.util.Iterator.