---
title: ICaptionsCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av de stängda undertexterna.
type: docs
url: /sv/com.aspose.slides/icaptionscollection/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

Representerar en samling av de stängda undertexterna.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar de stängda undertexterna på det angivna indexet. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Lägger till WebVTT-undertexter i slutet av samlingen. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Lägger till WebVTT-undertexter i slutet av samlingen från en ström. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Tar bort de angivna undertexterna från samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort undertexterna på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla undertexter från samlingen. |
| [getCount()](#getCount--) | Returnerar antalet element i samlingen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```


Returnerar de stängda undertexterna på det angivna indexet. Endast läsning [ICaptions](../../com.aspose.slides/icaptions).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```


Lägger till WebVTT-undertexter i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| label | java.lang.String | Etiketten för de stängda undertexterna. |
| filePath | java.lang.String | Sökvägen till WebVTT-filen. |

**Returnerar:**
[ICaptions](../../com.aspose.slides/icaptions) - Det tillagda [ICaptions](../../com.aspose.slides/icaptions)-instansen.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```


Lägger till WebVTT-undertexter i slutet av samlingen från en ström.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| label | java.lang.String | Etiketten för de stängda undertexterna. |
| stream | java.io.InputStream | Inmatningsströmmen som innehåller data i WebVTT-format. |

**Returnerar:**
[ICaptions](../../com.aspose.slides/icaptions) - Det tillagda [ICaptions](../../com.aspose.slides/icaptions)-instansen.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```


Tar bort de angivna undertexterna från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | De stängda undertexterna att ta bort. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Tar bort undertexterna på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Indexet för de stängda undertexterna som ska tas bort. |

### clear() {#clear--}
```
public abstract void clear()
```


Tar bort alla stängda undertexter från samlingen.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Returnerar antalet element i samlingen. Endast läsning int .

**Returnerar:**
int