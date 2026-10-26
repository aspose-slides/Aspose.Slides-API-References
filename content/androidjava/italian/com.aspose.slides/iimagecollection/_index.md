---
title: IImageCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta la collezione di PPImage.
type: docs
url: /it/com.aspose.slides/iimagecollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

Rappresenta la collezione di PPImage.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'immagine in base al suo indice. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Aggiunge un'immagine a una presentazione. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Aggiunge un'immagine a una presentazione da stream. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Crea e aggiunge un'immagine a una presentazione da stream. |
| [addImage(byte[] buffer)](#addImage-byte---) | Aggiunge un'immagine a una presentazione dal buffer specificato. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Aggiunge una copia di un'immagine da un'altra presentazione. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Aggiunge un'immagine a una presentazione da oggetto SVG. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```


Restituisce l'immagine per il suo indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice. |

**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage) - Immagine.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```


Aggiunge un'immagine a una presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Immagine da aggiungere.

--------------------

Questo metodo converte i metafili WMF/EMF in immagine raster PNG prima di inserirli in una presentazione. |

**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage) - Immagine aggiunta.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```


Aggiunge un'immagine a una presentazione da stream.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream da cui aggiungere l'immagine.

--------------------

Questo metodo può aggiungere metafili WMF/EMF a una presentazione senza convertirli in immagine raster PNG. |

**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage) - Immagine aggiunta.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Crea e aggiunge un'immagine a una presentazione da stream.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream da cui aggiungere il file immagine. |
| loadingStreamBehavior | int | Il comportamento che sarà applicato allo stream. |

**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage) - Aggiunta [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```


Aggiunge un'immagine a una presentazione dal buffer specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | byte[] | Buffer. |

**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage) - Immagine aggiunta.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```


Aggiunge una copia di un'immagine da un'altra presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Immagine sorgente. |

**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage) - Immagine aggiunta.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```


Aggiunge un'immagine a una presentazione da oggetto SVG.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Oggetto immagine SVG [ISvgImage](../../com.aspose.slides/isvgimage) |

**Restituisce:**
[IPPImage](../../com.aspose.slides/ippimage) - Immagine aggiunta.