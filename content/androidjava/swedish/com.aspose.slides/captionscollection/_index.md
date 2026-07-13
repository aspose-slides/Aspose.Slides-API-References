---
title: CaptionsCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av de stängda undertexterna.
type: docs
url: /sv/com.aspose.slides/captionscollection/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

Representerar en samling av de stängda undertexterna.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar de stängda undertexterna på det angivna indexet. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Lägger till WebVTT-stängda undertexter i slutet av samlingen. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Lägger till WebVTT-stängda undertexter i slutet av samlingen från en ström. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Tar bort de angivna stängda undertexterna från samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort de stängda undertexterna på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla stängda undertexter från samlingen. |
| [getCount()](#getCount--) | Returnerar antalet element i samlingen. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

Returnerar de stängda undertexterna på det angivna indexet. Skrivskyddad [ICaptions](../../com.aspose.slides/icaptions).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```

Lägger till WebVTT-stängda undertexter i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| label | java.lang.String | Etiketten för de stängda undertexterna. |
| filePath | java.lang.String | Sökvägen till WebVTT-filen. |

**Returnerar:**
[ICaptions](../../com.aspose.slides/icaptions) - Den tillagda [ICaptions](../../com.aspose.slides/icaptions)-instansen.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

Lägger till WebVTT-stängda undertexter i slutet av samlingen från en ström.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| label | java.lang.String | Etiketten för de stängda undertexterna. |
| stream | java.io.InputStream | Indataströmmen som innehåller data i WebVTT-format. |

**Returnerar:**
[ICaptions](../../com.aspose.slides/icaptions) - Den tillagda [ICaptions](../../com.aspose.slides/icaptions)-instansen.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

Tar bort de angivna stängda undertexterna från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | De stängda undertexterna att ta bort. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort de stängda undertexterna på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Indexet för de stängda undertexterna att ta bort. |

### clear() {#clear--}
```
public final void clear()
```

Tar bort alla stängda undertexter från samlingen.

### getCount() {#getCount--}
```
public final int getCount()
```

Returnerar antalet element i samlingen. Skrivskyddad int .

**Returnerar:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - En  System.Collections.Generic.IEnumerator1  som kan användas för att iterera genom samlingen.