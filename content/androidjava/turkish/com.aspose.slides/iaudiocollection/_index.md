---
title: IAudioCollection
second_title: Java API Referansı aracılığıyla Aspose.Slides for Android
description: Gömülü ses dosyalarının bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/iaudiocollection/
---
**Tüm Uygulanan Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Gömülü ses dosyalarının bir koleksiyonunu temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Başka bir sunumdan bir ses dosyasının kopyasını ekler. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Bir akıştan ses oluşturur ve bir sunuma ekler. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Bir akıştan ses oluşturur ve bir sunuma ekler. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Bir bayt dizisinden ses oluşturur ve bir sunuma ekler. |
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

Bir akıştan ses oluşturur ve bir sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Sesin ekleneceği akış. |

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio) - Eklenen ses.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Bir akıştan ses oluşturur ve bir sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Video sesinin ekleneceği akış. |
| loadingStreamBehavior | int | Akışa uygulanacak [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior). |

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio) - Eklenen ses.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

Bir bayt dizisinden ses oluşturur ve bir sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| audioData | byte[] | Ses baytları. |

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio) - Eklenen ses.