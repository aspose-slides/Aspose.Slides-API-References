---
title: IVideoCollection
second_title: Aspose.Slides for Android için Java API Referansı
description: Video nesnelerinin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ivideocollection/
---
**Uygulanan Tüm Arabirimler:**
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
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Akıştan bir videoyu oluşturur ve sunuma ekler. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Bayt dizisinden bir videoyu oluşturur ve sunuma ekler. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
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
public abstract IVideo addVideo(IVideo video)
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
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


Akıştan bir videoyu oluşturur ve sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Video dosyasını eklemek için akış. |
| loadingStreamBehavior | int | Akışa uygulanacak davranış. |

**Döndürür:**
[IVideo](../../com.aspose.slides/ivideo) - Eklenen [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```


Bayt dizisinden bir videoyu oluşturur ve sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| videoData | byte[] | Video baytları. |

**Döndürür:**
[IVideo](../../com.aspose.slides/ivideo) - Eklenen video.