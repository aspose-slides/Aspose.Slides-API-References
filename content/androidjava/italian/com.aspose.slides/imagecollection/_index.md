---
title: ImageCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta la collezione di PPImage.
type: docs
url: /it/com.aspose.slides/imagecollection/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

Rappresenta la collezione di PPImage.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce il numero di immagini nella collezione. |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Aggiunge una copia di un'immagine da un'altra presentazione. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Aggiunge un'immagine a una presentazione. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Aggiunge un'immagine a una presentazione dallo stream. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Crea e aggiunge un'immagine a una presentazione dallo stream. |
| [addImage(byte[] buffer)](#addImage-byte---) | Aggiunge un'immagine a una presentazione da un buffer specificato. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Aggiunge un'immagine a una presentazione da un oggetto Svg. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi della collezione nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
### size() {#size--}
```
public final int size()
```

Restituisce il numero di immagini nella collezione. Solo lettura  int .

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```

Ottiene l'elemento all'indice specificato. Solo lettura [IPPImage](../../com.aspose.slides/ippimage).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```

Aggiunge una copia di un'immagine da un'altra presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Immagine di origine. |

**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage) - Immagine aggiunta.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```

Aggiunge un'immagine a una presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Immagine da aggiungere.

--------------------

Questo metodo converte i metafile WMF/EMF in un'immagine raster PNG prima di inserirla in una presentazione. |

**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage) - Immagine aggiunta.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```

Aggiunge un'immagine a una presentazione dallo stream.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream da cui aggiungere l'immagine.

--------------------

Questo metodo può aggiungere i metafile WMF/EMF a una presentazione senza convertirli in un'immagine raster PNG. |

**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage) - Immagine aggiunta.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

Crea e aggiunge un'immagine a una presentazione dallo stream.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream da cui aggiungere il file immagine. |
| loadingStreamBehavior | int | Il comportamento che sarà applicato allo stream. |

**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage) - Aggiunto [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```

Aggiunge un'immagine a una presentazione da un buffer specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage) - Immagine aggiunta.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```

Aggiunge un'immagine a una presentazione da un oggetto Svg.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Oggetto immagine Svg [ISvgImage](../../com.aspose.slides/isvgimage) |

**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage) - Immagine aggiunta.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```

Restituisce un enumeratore che iterera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```

Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - Un java.util.Iterator per l'intera collezione.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia tutti gli elementi della collezione nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice di partenza nell'array di destinazione. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). Solo lettura  boolean .

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce una radice di sincronizzazione. Solo lettura  Object .

**Restituisce:**
java.lang.Object