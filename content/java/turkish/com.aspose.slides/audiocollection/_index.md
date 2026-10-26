---
title: AudioCollection
second_title: Aspose.Slides for Java API Referansı
description: Gömülü ses dosyalarının bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/audiocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Gömülü ses dosyalarının bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyondaki ses dosyalarının sayısını döndürür. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Başka bir sunumdan bir ses dosyasının kopyasını ekler. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Akıştan bir ses oluşturur ve bir sunuma ekler. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Akıştan bir ses oluşturur ve bir sunuma ekler. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Bayt dizisinden bir ses oluşturur ve bir sunuma ekler. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sesleri belirtilen indeksten başlayarak belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [iterator()](#iterator--) | Koleksiyon üzerinde yineleme yapan bir döngücü döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
### size() {#size--}
```
public final int size()
```

Koleksiyondaki ses dosyalarının sayısını döndürür. Yalnızca okunur int.

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

Belirtilen indeksteki öğeyi alır. Yalnızca okunur [IAudio](../../com.aspose.slides/iaudio).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
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
public final IAudio addAudio(InputStream stream)
```

Akıştan bir ses oluşturur ve bir sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Ses eklemek için akış. |

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio) - Eklenen ses.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Akıştan bir ses oluşturur ve bir sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | java.io.InputStream | Video ses eklemek için akış. |
| loadingStreamBehavior | int | Akışa uygulanacak davranış. |

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio) - Eklenen ses.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

Bayt dizisinden bir ses oluşturur ve bir sunuma ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| audioData | byte[] | Ses baytları. |

**Döndürür:**
[IAudio](../../com.aspose.slides/iaudio) - Eklenen ses.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sesleri belirtilen indeksten başlayarak belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Dizi. |
| index | int | İndeks. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Yalnızca okunur boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Yalnızca okunur Object.

**Döndürür:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

Koleksiyon üzerinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Bir IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Tüm koleksiyon için bir java.util.Iterator.