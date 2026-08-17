---
title: IVideoCollection
second_title: Aspose.Slides için Java API Referansı
description: Video nesnelerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ivideocollection/
---
**Tüm Uygulanan Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Video nesnelerinin bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Başka bir sunumdan bir video dosyasının kopyasını ekler. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Akıştan bir video oluşturur ve sunuma ekler. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Bayt dizisinden bir video oluşturur ve sunuma ekler. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```


Belirtilen indeksteki öğeyi alır. Salt-okunur [IVideo](../../com.aspose.slides/ivideo).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```


Başka bir sunumdan bir video dosyasının kopyasını ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Kaynak video. |

**Dönüş:**
[IVideo](../../com.aspose.slides/ivideo) - Eklenen video.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


Akıştan bir video oluşturur ve sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Video dosyasının ekleneceği akış. |
| loadingStreamBehavior | int | Akışa uygulanacak davranış. |

**Dönüş:**
[IVideo](../../com.aspose.slides/ivideo) - Eklenen [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```


Bayt dizisinden bir video oluşturur ve sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| videoData | byte[] | Video baytları. |

**Dönüş:**
[IVideo](../../com.aspose.slides/ivideo) - Eklenen video.