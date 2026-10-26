---
title: IAudioCollection
second_title: Aspose.Slides için Java API Referansı
description: Gömülü ses dosyalarının bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/iaudiocollection/
---
**Tüm Uygulanan Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Gömülü ses dosyalarının bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Başka bir sunumdan bir ses dosyasının kopyasını ekler. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Bir akıştan bir sunuma ses oluşturur ve ekler. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Bir akıştan bir sunuma ses oluşturur ve ekler. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Bir bayt dizisinden bir sunuma ses oluşturur ve ekler. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```


Belirtilen indeksteki öğeyi alır. Salt okunur [IAudio](../../com.aspose.slides/iaudio).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```


Başka bir sunumdan bir ses dosyasının kopyasını ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Kaynak ses. |

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio) - Eklenen ses.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```


Bir akıştan bir sunuma ses oluşturur ve ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Sesten eklenecek akış. |

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio) - Eklenen ses.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


Bir akıştan bir sunuma ses oluşturur ve ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Video sesini eklemek için akış. |
| loadingStreamBehavior | int | Akışa uygulanacak [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior). |

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio) - Eklenen ses.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```


Bir bayt dizisinden bir sunuma ses oluşturur ve ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| audioData | byte[] | Ses baytları. |

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio) - Eklenen ses.